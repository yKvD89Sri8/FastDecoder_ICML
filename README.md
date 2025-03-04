# Fastdecoder
An optimized n-best strategies for high time and memory efficiency code generation

## First Step: Generate Python Codes for the tasks with:
```code
python src/code_generation_for_task.py
```

## Second Step: add memory and time profiler to the generated py code with:
```code
python add_profiler_to_py_code.py
```

## Third Step: Calculate the Time Efficiency for each python code with corresponding profiler:
```code
#for time efficiency calculation
python time_efficiency_profile.py

#for memory efficiency calculation
python memory_efficiency_profile.py
```

## Fourth Step: Collect the profile report and generate the final statistical results:
```code
python read_dat_to_generate_final_result.py
``` 
