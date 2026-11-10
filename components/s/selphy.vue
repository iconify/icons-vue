<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7fu--b6v"/><path class="dc1ljbc2t"/><path class="fge5nbc9s"/><path class="lkwxjy72a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:selphy" /></template>
<style>
.b7fu--b6v {
  fill: currentColor;
  d: path("M13.828 16.175a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.dc1ljbc2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.373 10.246h11.86v14.163H5.19V10.246h7.592");
}

.fge5nbc9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.614 19.33c1.462.207 2.616.385 3.98-.587c-.157 1.669.574 2.579 1.484 3.741c.91-1.162 1.64-2.072 1.482-3.74c1.365.97 2.52.793 3.98.586c-.55-1.37-.973-2.458-2.497-3.155c1.524-.696 1.947-1.785 2.498-3.154c-1.461-.207-2.615-.385-3.98.587c.158-1.669-.573-2.579-1.483-3.741c-.91 1.162-1.641 2.072-1.483 3.74c-1.366-.97-2.52-.793-3.98-.586c.55 1.37.973 2.458 2.497 3.154c-1.523.697-1.946 1.786-2.498 3.155m17.617-2.16H42.81v20.963H14.407V24.41");
}

.lkwxjy72a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.357 21.244h13.16V34.06h-19.82v-9.39m9.91-3.179v12.32m-9.314-6.16h9.315");
}

</style>
