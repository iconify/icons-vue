<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="dayjs-bgu"/><path class="dr1p0554f"/></g><path class="a0yh6z_ij"/><path class="boyowm1xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:users-group-rounded-bold-duotone" /></template>
<style>
.a0yh6z_ij {
  fill: currentColor;
  d: path("M9 13.001C12.866 13.001 16 14.7918 16 17.001C16 19.2101 12.866 21.001 9 21.001C5.13401 21.001 2 19.2101 2 17.001C2 14.7918 5.13401 13.001 9 13.001Z");
}

.boyowm1xr {
  fill: currentColor;
  d: path("M9 2C11.2091 2 13 3.79086 13 6C13 8.20914 11.2091 10 9 10C6.79086 10 5 8.20914 5 6C5 3.79086 6.79086 2 9 2Z");
}

.dayjs-bgu {
  d: path("M16 14C18.7614 14 21 15.3431 21 17C21 18.6569 18.7614 20 16 20C13.2386 20 11 18.6569 11 17C11 15.3431 13.2386 14 16 14Z");
}

.dr1p0554f {
  d: path("M15 3C16.6569 3 18 4.34315 18 6C18 7.65685 16.6569 9 15 9C13.3431 9 12 7.65685 12 6C12 4.34315 13.3431 3 15 3Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
