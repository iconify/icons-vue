<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b0gz0kbdd"/><path class="kunl_hbfp"/><path class="yn1ssabas"/><path class="v2qbj0dju"/><path class="l7xccfb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:xwiki-icon" /></template>
<style>
.b0gz0kbdd {
  fill: var(--svg-color--70b700, #70b700);
  d: path("M127.612 0a8.85 8.85 0 0 1 8.844 8.51l.006.34v39.668a8.85 8.85 0 0 1-17.694.34l-.006-.34V8.85a8.85 8.85 0 0 1 8.85-8.85");
}

.kunl_hbfp {
  fill: var(--svg-color--f70, #f70);
  d: path("M247.143 117.992a8.85 8.85 0 0 1 .395 17.692l-.395.009h-39.667A8.85 8.85 0 0 1 207.08 118l.395-.009z");
}

.l7xccfb1s {
  fill: var(--svg-color--505052, #505052);
  d: path("M224.319 17.102c6.28 5.496 7.018 14.97 1.745 21.367l-.3.352l-77.707 88.791l77.707 88.791c5.599 6.397 4.951 16.121-1.445 21.72c-6.28 5.496-15.769 4.972-21.41-1.103l-.31-.343l-74.996-85.694l-74.995 85.694c-5.599 6.396-15.323 7.044-21.72 1.445c-6.28-5.496-7.018-14.97-1.745-21.366l.3-.353l77.706-88.79L29.443 38.82c-5.599-6.397-4.951-16.121 1.446-21.72c6.28-5.496 15.768-4.972 21.41 1.103l.309.344l74.995 85.692L202.6 18.548c5.598-6.397 15.322-7.045 21.719-1.446");
}

.v2qbj0dju {
  fill: var(--svg-color--0087cb, #0087cb);
  d: path("M8.85 135.693A8.85 8.85 0 0 1 8.456 118l.394-.009h39.668a8.85 8.85 0 0 1 .394 17.692l-.394.009z");
}

.yn1ssabas {
  fill: var(--svg-color--red, red);
  d: path("M136.462 246.374a8.85 8.85 0 0 1-17.692.394l-.008-.394v-39.668a8.85 8.85 0 0 1 17.692-.394l.008.394z");
}

</style>
