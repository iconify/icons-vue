<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rmn0ob2lq"/><path class="rcdmxbcdv"/><path class="rukq87b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yourlocalweather" /></template>
<style>
.rcdmxbcdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 17.675a2.5 2.5 0 0 0-1.492.536c-1.686-2.743-4.913-2.714-6.57.06c-2-1.478-4.915.59-4.469 3.385c.553 2.72 3.784 2.873 7.649 2.661c5.585-.306 6.665.09 7.732-1.739A3.442 3.442 0 0 0 30 17.675");
}

.rmn0ob2lq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a13.09 13.09 0 0 0-13.091 13.091c0 10.251 10 22.612 12.611 25.632a.8.8 0 0 0 1.21 0c2.55-3 12.361-15.381 12.361-25.632A13.09 13.09 0 0 0 24 4.5");
}

.rukq87b3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.975 15.992l-.034-.132a3.62 3.62 0 1 0-6.263 3.282m.661-7.206l-.612-1.425m-2.093 4.268l-1.441-.575m1.495 4.716l-1.426.612m8.341-7.65l.575-1.441m1.899 4.208l1.426-.612");
}

</style>
