<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la46bdbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pedal-bike-rounded" /></template>
<style>
.la46bdbvm {
  fill: currentColor;
  d: path("M5 19.5q-1.914 0-3.207-1.293T.5 15q0-1.875 1.318-3.207T5 10.462q1.714 0 2.997 1.16q1.284 1.159 1.48 2.878h1.765l-2.146-6H8q-.213 0-.357-.143T7.5 8t.143-.357T8 7.5h3q.214 0 .357.143T11.5 8t-.143.357T11 8.5h-.83l.696 1.962h5.915L15.1 5.846q-.058-.173-.192-.26q-.135-.086-.308-.086H13q-.213 0-.357-.143T12.5 5t.143-.357T13 4.5h1.6q.477 0 .874.264q.397.263.565.728l1.815 4.958H19q1.864 0 3.182 1.318T23.5 14.95q0 1.87-1.315 3.19q-1.316 1.322-3.185 1.322q-1.723 0-2.98-1.135T14.523 15.5H9.477q-.196 1.725-1.498 2.863T5 19.5m3.454-4v-1H6q-.213 0-.357.143T5.5 15t.143.357T6 15.5zm3.9-1h2.169q.087-.69.51-1.623q.425-.933 1.236-1.416h-5.05zm4.965-2.57l.812 2.297q.067.189.262.277t.384.015t.277-.265t.015-.381l-.861-2.296z");
}

</style>
