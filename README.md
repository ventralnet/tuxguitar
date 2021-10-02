1. Open up intellij
2. Open File or project
3. navigate to <tuxguitar_root>/build-scripts/tuxguitar-linux-x86
4. Let the project load
5. Load file TGMain.java and try to run it (it will fail, just creating a run configuration)
6. go into run configuration for tgmain
7. click 'modify options' link
8. select 'Add dependencies with 'provided' scope to classpath

click ok

9. in project list right click TuxGuitar project and 'Open Module Settings'
10. go to modules and click on tuxguitar module
11. go to dependencies tab
12. add module dependency 'tuxguitar-ui-toolkit-swt'
13. next add library and select ...org.eclipse.swt.gtk.linux.x86_64
14. in main screen expand TuxGuitar project right click 'share' 'mark resources root' 
