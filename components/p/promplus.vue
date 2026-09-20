<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzd70fbxk"/><path class="hhdx4hbki"/><path class="ljqpacz0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:promplus" /></template>
<style>
.hhdx4hbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.253 29.454c3.209 2.45 5.918 4.91 8.052 7.623c4.055-6.23 12.32-15.289 19.17-19.492");
}

.hzd70fbxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.526 24.358c5.124-5.227 14.846-8.137 25.663-5.745M13.67 33.578c3.242 3.538 7.159 8.622 8.852 11.716c2.557-4.857 9.856-14.853 17.969-19.643");
}

.ljqpacz0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.605 20.04c-.748 0-1.35.602-1.35 1.35v2.066h-2.068c-.748 0-1.349.604-1.349 1.351v1.068c0 .747.601 1.35 1.35 1.35h2.066v2.068c0 .747.603 1.348 1.351 1.348h1.068c.748 0 1.349-.6 1.349-1.348v-2.067h2.069c.748 0 1.349-.604 1.349-1.351v-1.068c0-.747-.601-1.35-1.35-1.35h-2.068v-2.068c0-.747-.601-1.348-1.35-1.348zm7.845-9.916a7.418 7.418 0 1 1-14.837 0a7.418 7.418 0 0 1 14.837 0");
}

</style>
