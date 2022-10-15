## FIT3179 Data Visualisation Assignment 2

#### **The Webpage URL for the Visualisation:**
> https://hongjchang.github.io/FIT3179Assignment2/

**Main Task:** To create visualisations with Vega-Lite for Assignment 2.

**Created By:** me (hongjchang)

**Date Created:** 22/09/2022

**Date Completed:** 17/10/2022

**Notes:**
- To find the submitted version, it is `commit_num`.
- This whole directory was pre-created after the completion of Week9Homework.
- Then, the html and style.css files are modified based on **Week 10 Lab Answer** folder & **Week10Homework** directory. 
- This duplication however does not apply to GitHub repository.
- All map topojson files are using `1:110m physical and cultural` from [this website](https://www.naturalearthdata.com)

**References:**
- `index.html` formattings:
    - Flaticon (2022). Icon used for webpage's logo icon/favicon. Retrieved from: https://www.flaticon.com/free-icon/multiple-users-silhouette_33308?term=population&page=1&position=2&page=1&position=2&related_id=33308&origin=search
    - Toptal (2022). Information icon. Retrieved from: https://www.toptal.com/designers/htmlarrows/symbols/information-source/
    - W3Schools (2022). Create tooltips. Retrieved from: https://www.w3schools.com/howto/howto_css_tooltip.asp
    - StackOverflow (2014). How to make a closable banner in pure javascript. Retrieved from: https://stackoverflow.com/a/26957495

- From Week10Homework:
    - The `oceans.topojson` file **had changed** and was adapted from [here](https://raw.githubusercontent.com/FIT3179/Vega-Lite/main/7_others/oceans.topojson).
    - The countries csv file for `choropleth_map.vg.json` file was adapted [here](https://raw.githubusercontent.com/FIT3179/Vega-Lite/main/3_choropleth_map/data/countryInfo.csv) and [here](https://edstem.org/au/courses/8853/discussion/1051935?answer=2351836).
    - Stacked bar chart for religions chart. https://vega.github.io/vega-lite/examples/stacked_bar_count_corner_radius_mark.html
    - The `religion.vg.json` file is adapted from Week10 Lab Part 3 Repeating Choropleth Map.
    - Year filter in `religion.vg.json` file: [Link](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQAWTgATGklkACGGwYQ4hnACcaUCzjhXDEZgytNDACgBMABgCMvvx+fgCUiiA6SJgoqKBughpYuPhEVkgA7tR0jExmjlBymHCymJSFCAQAYgCSACoAzP4A7ACcBABqfPwAMiIEyDSyBABsAPpIOsQGdjpjcAAeSAg4ahAEUTEEJvlj1rZwY0wAnmMuee5jgnJkYwBmbFbIZVAQxCAAvko4SOkIEGgANqgWTLdToY5wX5nOBqKCYCLTQQMcF+fxiJRMIY6NCgIY4BgI9DpWRkdRKBBDNBo3wUpALam+bz+JQQYo4NAskCghDgkAATShVlQhk+XxBYI0AC82GwEFc4KREkokSi0A1fJraSAsbIcXEQPjCRoSWSIpT5KgGmJNXSGagRlrtWy4BzUIFtTy+QAtWUIEVihQS3kaOylRxjTBsRFIZHgwH+AAsGP4DWalGTAF1MdjcYbZASiSBzHCEUo2DgVHIAahAQnkwpU+mswp64nKA1G2nKCNs23KK0uyNKN4+0n0yymz3M9mQIIkExYTXAVpYUxTFZZBYAMIAIQAIhEAOJwWE3CK7kp6MjRpQAZVj6lnXo0miQOEM25KmCscADHw+WdiEKWQoGiIFQAyGgdHoUMiiQIZHAieAaDILA0BtbVrDYSQ4HhdhLVATBjgcDQ4AARwYGhf3hAwyAYecrAiMNiiYg1FmsUNvwjKNPlZMC1DzDi2JAGU5QVJVAznJBITY4FImiWJ4isRJ0GSPBCAIdIsloehXHMKwQOKUpyjlap6iaNpOm6PpigGBDhnGSZplA3R5iWFY1g2RTOhqbcxh6AB5bcAEEenqfkxgABUCnp+SPQKADkxjvAAJKKpBkeQlAeJ5wINYjSPQKMcBwrKIjuKFMDcPkOj8gLgrCiLoti+KkpS9KpJ-AwIFyhAIJAASoAY6I+QAcn3RTDBoCBDFkNhMEMJBphoecmDUaajDGwwAGpDE2BgEEobCHCsFQ4AgShEpCzQAFEIiQGtuQW9RALpKwAGs80KvkyTYCAYHfckQDuVbVJAABiHRoYiNkrDYD6+QyGARFhn8EbgAB1aDYPdL4QBKQo9FJb7ZUEFQ3VAUHYX1Z7ijFcUQB+P5l2DPlrigGFS1h2E8KJIiSL5UqhjLAnQLYYmyGXSILqgGxKwIkBMwA2dutkXrHn62tQGuBGGDdOc2AEuhjgq+GtdATYlJABIkmwDS0kybI9LyAyjO-UzKlqRoWnaLoKF6fpBkciYphmNzFmWVYLu8rY6v8oLQvCupIpiuKEuStKMukOQKs1-KBaK5QKzK3OcqqmqNHjhqk+atO2szzqAKURHTfQE7HHOy7rruviQEejQ-r4qnVtYjRIV+TwDqOierFCQwAF4F8MWeub5z5Z2QT7vsFwe4H+wHSNZdHEY0CG7gvtH4cR7GYJgNBfEoMR8cJiWhjIPMAaBvNqcEWmh6UD9Pepd5D4x0LLeWVZCIgxoDTDQHNYwmz7qDQQqkR5wPbjYOwEQgHoEogYFQMQVCkBwaoPk2g9AGEMFFLBFhPAhQAKr7nCPxR8eYdBygckCRMTpaTol4bOLgiA+S-h0ACfGagyR6h-vnIsI5xH4yjGwcmNA3TyV-rTBBwhiKkMwIJdAd5XDuGHjAjBTNaF5zykWJQgCyGvl0PoIwNCDheEYcwkxGjx5Cl0fogU3jAG72KogUq6RlTKBoLyBhsg6BeN+BvFWjMoJ3zgqUBySElAoTQkSDU2p5yyQGlvL66BhBbhwSSDWTwBooLHgaZmyx4FGzXvCMUs5X6SzzPadBf9YlMQCUXYoKxHixgegsGaeYyA2H1HcWM5hFF2PQIKOJ+M26gCQGQCZfB6boGWo4NZwNPGYIODgwJIB8GlDoNEGgJDbF6PIQ4qhzi7CuKYSw-uoyaxU1kRoeRDNGaFJ3v0xYotEFkEtCAGwWSIhMEerCRCGh1zYDlBEe0IAkmwSUG3XwL9xbtIKkCvMIE9BQO+hdIsABCGa+44Cgy3DoTwHMmllC0SbV5qo+RhR6IYO8DDdwMIAEq7jvH3NlQkFicWKY0ksfNKDMp0QBBJysgA)
    - The `choropleth_map.vg.json` file is adapted from Week8 Lab Part 3 Choropleth Map & Week10 Lab Part1.2 Earthquake map & [here](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQSBpjYQaALzhpQAJzgbtaTHoZwAvkoAmSTClSgGewWgzY8hAnqQB3anSMTAwQcHpQcphwspiUEQgEAGIAkgAqAMwAjADsAJwEAGp8-AAyIgTINLIE6QD6sGx6bDiCcPS1yDgE0gSycLWZmQAMCLVI1ghVtUP1bAwxejSGlGo4bNJyiiAAZo3ImLogmACeODroq+sy8krbcHbO5yB9A8Oj45Oy07PzpksQIAsVhAxAisigdjQAG1QJg6K03ABhADyBWSABF+JlcgACRFybY0PQIODWPFIUIQHEACmGOORUEwOIATENWQBKLa+GjWehoAAcQyGSngNDIWDQABYhUocE1JHBGex5I4jqcnnAAI4MJCCACiSD0fOBgiQxzC0NhPlkEF2xMtIAhgigDFNUTcAHJ0XYkDiaFTZGwmUhiEgaKamK0-bIcR6cQBqHG2TAMBCUOXNMJw5YAOQAggBZPVbCluQPuiwAXSUyD0AGtDiczm4yHB1DAkM3buHXOhhOLMGQfMcthBTGw609fDARIClNEItYqmRG2w2II4ThDoS4IJrGWgzogVZQMmHE4XG4sLh8EQfP5aPRmCEwmCojE4mwEikMjl8kUKFKcpKmqbJaiDeA9AgAg2Cge4bRWZork2W49khVUmyeS4NhuHZ7hTAw3Fg+CASBGtDQbDD1RbNsIA7Lsdh7NwIDrY5I3MQETxAM9DmcXt3BvLx7wCJ9glCcJImiWJ4iSNIsjyQpijKKIKjDapmVqCBjgQJh1w6TtumggB1Ro9wLTsjMCABxHw4RdVoIEQtYcK2O19kbaiLiQlzbnwx4y36QYRlqIc7BoezDFqdIhk48j6w85t0FbdtOx0btBF7WRXUEJQxyaSc3H7LBQpHMirSQG03IdQQ1zrBgt3QDMziNf5KHzItXKaBBDh41U+KvDxb28PwRKCF8JJiKTP2-OS-0UwDlNEECanqGBGmaVp2k6AgzwICJiB5AYZmGWpWVZOIIGIOcQEnEd0HxX49BHbtd2sAFUChEA8yVUgtnxWRCWJUktgABWaV0ws2SsysdXV7LsJ5k1TSh-sBklrB2h40zBnAIbhOQcQAKhxYYhRipRS3ugkiXRnFmpJ4Uybp8G3WVQFqxAWtKNhTyQGSujUtHccCvQadZ2BHBDSQBB3phZ5paeCJHuOABlXdFXx3DQlaRkEqeNYqgOIEOYXNgl1kFdVQiGq9G3JY9yRamgbJenhgUJm1lx1mULVRKQG1Cq4XsOFftyp1zh5v36AMOj133GwvzU6FMgUN3SY561W2hEAAGJtmsJg4H5MQtjz6x+WsdIoFLuAADYxDEIZ49zpBa-SWuhnSEBoeBNR103B0dwdxqmma7NHPa4slEwg9Pl1LYg4RKnlbnUAh-3dBvpDtLfaeAOYjoMLfq49fHYBmnSTpsIGfdoVma9yHcJn9B96Do+d7c9CQEoZltnZmHTAVVtHsaqtV6puCalmVqk9Opfh6j6Xil50DXk8HeEaj4xriTfFNGSP55L-iUsBNSK0Gij02jAfSXRdpKwWMcZIAM2AXSusCW6ZYFauXtm9bOrMUzWB3jVC2dAGB8O7sbOK3Nd5uCiAADyNvOcEZtlyHAEY+YREdGKvUKnIVRIjp681fofbe10eFqLtpovsYVeE72fv7HUB9g40GPtPOAsizHDxAJAlquZCxT0kegQMc9XDAmaEgKAdA7qgDBEuTWjZDAHHQEjBAUIPSePHm1HxHpKw4gALzZNjIiGcsgkBxgAD4lKTFjZJqToEZKybk2MAAhHwmhwylPKYkqpo8oHeKLJknJeSPR5hCIA4QxScRlIqSmJJKSuleInrU-psZzKmmOBoMZEzJmpk6ZmOZ6Tel1IGQATUQNENpOJNnTOqT0vUfT6kegAKqyBEGSFWwdDA4jYNsHEeYSSLAhB6LYoZBAcVQJkYEQKQVDGPNDBQoBuS8hgGgbIMojjWmAfaD6oAaoTnASPHZaSYG3C6vA+wiD+IoKGsJDBz4sGSQ-Lg2aCkAICEWqpKoJC1pkLaBQ7a1C2AHWsEdIVZ0hhMOuqw5etCOGvVll9H6O9UYX2bjjPGbMe6wths6PGiMsYoydujTGUzKAqu9jGYmpMhQlneiARVzsr56Bvh7Fmj9V6MQ3BaVUksfDdXQDQ0wqt1ZKh9ogHAJw0DbF1KEMRnMKJ6zcEwQ011Tbm0tqAaRbiN42v1ZfV2jM76e1VT7GxBiHGhyOPCJ4traaIgpIYa6ESNHuKufMjqei-YBKqPPaeFa0BZQytCpQYJCSpqBEAA)
    - The zoom in out slider in `choropleth_map.vg.json` is adapted from [here](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQmOoLhoQAWTgATGklkACGGwYQ4hnACcaUCzjhXDEZgytNDACgBMABgCMvvx+fgCUiiA6SJgoqKBughpYuPhEVkgA7tR0jExmjlBymHCymJSFCAQAYgCSACoAzP4A7ACcBABqfPwAMiIEyDSyBABsAPpIOsQGdjpjcAAeSAg4ahAEUTEEJvlj1rZwY0wAnmMuee5jgnJkYwBmbFbIZVAQxCAAvko4SOkIEGgANqgWTLdToY5wX5nOBqKCYCLTQQMcF+fxiJRMIY6NCgIY4BgI9DpWRkdRKBBDNBo3wUpALam+bz+JQQYo4NAskCghDgkAATShVlQhk+XxBYI0AC82GwEFc4KREkokSi0A1fJraSAsbIcXEQPjCRoSWSIpT5KgGmJNXSGagRlrtWy4BzUIFtTy+QAtWUIEVihQS3kaOylRxjTBsRFIZHgwH+AAsGP4DWalGTAF1MdjcYbZASiSBzHCEUo2DgVHIAahAQnkwpU+mswp64nKA1G2nKCNs23KK0uyNKN4+0n0yymz3M9mQIIkExYTXAVpYUxTFZZBYAMIAIQAIhEAOJwWE3CK7kp6MjRpQAZVj6lnXo0miQOEM25KmCscADHw+WdiEKWQoGiIFQAyGgdHoUMiiQIZHAieAaDILA0BtbVrDYSQ4HhdhLVATBjgcDQ4AARwYGhf3hAwyAYecrAiMNiiYg1FmsUNvwjKNPlZMC1DzDi2JAGU5QVJVAznJBITY4FImiWJ4isRJ0GSPBCAIdIsloehXHMKwQOKUpyjlap6iaNpOm6PpigGBDhnGSZplA3R5iWFY1g2RTOhqbcxh6AB5bcAEEenqfkxgABUCnp+SPQKADkxjvAAJKKpBkeQlAeJ5wINYjSPQKMcBwrKIjuKFMDcPkOj8gLgrCiLoti+KkpS9KpJ-AwIFyhAIJAASoAY6I+QAcn3RTDBoCBDFkNhMEMJBphoecmDUaajDGwwAGpDE2BgEEobCHCsFQ4AgShEpCzQAFEIiQGtuQW9RALpKwAGs80KvkyTYCAYHfckQDuVbVJAABiHRoYiNkrDYD6+QyGARFhn8EbgAB1aDYPdL4QBKQo9FJb7ZUEFQ3VAUHYX1Z7ijFcUQB+P5l2DPlrigGFS1h2E8KJIiSL5UqhjLAnQLYYmyGXSILqgGxKwIkBMwA2dutkXrHn62tQGuBGGDdOc2AEuhjgq+GtdATYlJABIkmwDS0kybI9LyAyjO-UzKlqRoWnaLoKF6fpBkciYphmNzFmWVYLu8rY6v8oLQvCupIpiuKEuStKMukOQKs1-KBaK5QKzK3OcqqmqNHjhqk+atO2szzqAKURHTfQE7HHOy7rruviQEejQ-r4qnVtYjRIV+TwDqOierFCQwAF4F8MWeub5z5Z2QT7vsFwe4H+wHSNZdHEY0CG7gvtH4cR7GYJgNBfEoMR8cJiWhjIPMAaBvNqcEWmh6UD9Pepd5D4x0LLeWVZCIgxoDTDQHNYwmz7qDQQqkR5wPbjYOwEQgHoEogYFQMQVCkBwaoPk2g9AGEMFFLBFhPAhQAKr7nCPxR8eYdBygckCRMTpaTol4bOLgiA+S-h0ACfGagyR6h-vnIsI5xH4yjGwcmNA3TyV-rTBBwhiKkMwIJdAd5XDuGHjAjBTNaF5zykWJQgCyGvl0PoIwNCDheEYcwkxGjx5Cl0fogU3jAG72KogUq6RlTKBoLyBhsg6BeN+BvFWjMoJ3zgqUBySElAoTQkSDU2p5yyQGlvL66BhBbhwSSDWTwBooLHgaZmyx4FGzXvCMUs5X6SzzPadBf9YlMQCUXYoKxHixgegsGaeYyA2H1HcWM5hFF2PQIKOJ+M26gCQGQCZfB6boGWo4NZwNPGYIODgwJIB8GlDoNEGgJDbF6PIQ4qhzi7CuKYSw-uoyaxU1kRoeRDNGaFJ3v0xYotEFkEtCAGwWSIhMEerCRCGh1zYDlBEe0IAkmwSUG3XwL9xbtIKkCvMIE9BQO+hdIsABCGa+44Cgy3DoTwHMmllC0SbV5qo+RhR6IYO8DDdwMIAEq7jvH3NlQkFicWKY0ksfNKDMp0QBBJysgA)
    - The up down left right rotation in `choropleth_map.vg.json` is adapted from https://vega.github.io/vega-lite/examples/interactive_geo_earthquakes.html

**Repository Link:** https://github.com/hongjchang/FIT3179Assignment2