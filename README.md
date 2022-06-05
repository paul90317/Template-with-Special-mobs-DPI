# Template with Special Mobs DPI
This is the template of special mobs data pack programming interface.  
which means if you don't want to touch any code, you can leave here.
### Checkout [Special Mobs Event Loop](https://github.com/paul90317/Special-Mobs#event-loop) to know how to use this.
### Feel free to copy and use this template.
## Directery Structure in data/
```txt
├───<yournamespace>
│   └───functions
│           <yourfunction>.mcfunction
│           ...
└───spm_dpi
    └───tags
        ├───entity_types
        │       special_mob.json
        │       
        └───functions
            ├───mob
            │       on_death.json
            │       on_hurt.json
            │       on_set.json
            │       on_tick.json
            │
            └───nature_spawn
                │   dimension_type.json
                │
                └───in
                        overworld.json
                        the_end.json
                        the_nether.json
```
