## Special notes
I'm the first person that who made search browser tabs work with firefox using extension.
and time goes by, similar extensions appeared on firefox addons market.  

It's good to hear.  

I'm thinking I made some little changes on this world, feel good.  

Someone think it's nothing, but I feel good and weired.

Here's my [original one](https://github.com/luceat-lux-vestra/alfred-tabs-improved)
I think it's not usable now, but it's memorable to me. haha.

## Supported Browsers - I guess it's working well but not all browseres tested.
```ruby
      @supported_browsers ||= [
        'Safari',
        'Safari Technology Preview',
        'WebKit',
        'Google Chrome',
        'Google Chrome Beta',
        'Google Chrome Dev',
        'Google Chrome Canary',
        'Chromium',
        'Opera',
        'Opera Beta',
        'Opera Developer',
        'Opera GX',
        'Vivaldi',
        'Vivaldi Beta',
        'Vivaldi Snapshot',
        'Microsoft Edge',
        'Microsoft Edge Beta',
        'Microsoft Edge Dev',
        'Microsoft Edge Canary',
        'Brave Browser',
        'Brave Browser Beta',
        'Brave Browser Dev',
        'Brave Browser Nightly'
      ]
```
## Changes
> Icon for workflow  
> Icons for search result: document.icns -> app.icns, compass.icns  
> `Search Safari and Chrome Tabs.alfredworkflow` icons just from `alfred-tabs` and applied above changes  
> If you prefer original icons, use `SearchTabs.alfredworkflow`  

Search tabs in Safari and Chrome (also supports Safari Technology Preview, WebKit, Chromium, Chrome Canary and Vivaldi)

Just added `Vivaldi` support to `Search Safari and Chrome Tabs` by `ClintonStrong`.

Original :  [Packal](http://www.packal.org/workflow/search-safari-and-chrome-tabs), [Forum](https://www.alfredforum.com/topic/236-search-safari-and-chrome-tabs-updated-feb-8-2014/)

I hope someone figures out a way to support `Firefox`.