<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nimy6sbzy"/><path class="f-d5lbbbc"/><path class="u1zjnsb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taobao" /></template>
<style>
.f-d5lbbbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.644 12.882a49 49 0 0 1 13.265-2.64c8.201-.296 10.77 4.217 11.317 9.601c.834 8.192-.151 13.39-4.13 17.326c-2.316 2.29-6.314 4.882-14.053.482M20.88 20.12h12.658m-6.978.212v13.416m-10.206-7.253h19.47m-4.076 2.038l1.716 6.007");
}

.nimy6sbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.403a15.8 15.8 0 0 1 4.827 4.291m-4.559 4.881c10.529 7.165 6.8 13.964.805 20.704M19.412 7.721c-.267 8.067-3.715 10.308-6.544 13.034");
}

.u1zjnsb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.711 31.905c-2.233.704-13.314 5.632-15.767-2.353m6.597-12.98l-5.149 6.865");
}

</style>
