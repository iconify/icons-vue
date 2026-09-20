<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsg5fcbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-full-outline-sharp" /></template>
<style>
.fsg5fcbdp {
  fill: currentColor;
  d: path("M11.062 8.5q-1.414 0-2.748.378T5.796 9.992L6.923 20h10.173l1.177-10.5h-.758q-.911 0-1.686-.137t-2.106-.519q-.633-.194-1.306-.269T11.062 8.5m-5.381.433q1.256-.714 2.618-1.073q1.363-.36 2.788-.36q.73 0 1.458.09t1.434.29q1.327.37 2.018.495q.692.125 1.5.125h.886l.483-4.5H5.116zM6.027 21L4 3h16l-2.008 18zm5.035-1h6.034H6.923z");
}

</style>
