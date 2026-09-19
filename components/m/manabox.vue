<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="re8k0m27n"/><path class="hsef79bdy"/><path class="f71cly0hj"/><path class="b105oi_ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:manabox" /></template>
<style>
.b105oi_ok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.742 17.5v13L24 37l11.258-6.5v-13L24 11zM24 37v8.5m11.258-28l7.362-4.25M12.742 17.5L5.38 13.25M24 11V2.5m-11.258 28L5.38 34.75m29.878-4.25l7.362 4.25");
}

.f71cly0hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.639 19.75L24 24l7.361-4.25M24 24v8.5");
}

.hsef79bdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.639 19.75v8.5L24 32.5l7.361-4.25v-8.5L24 15.5z");
}

.re8k0m27n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.38 13.25v21.5L24 45.5l18.62-10.75v-21.5L24 2.5z");
}

</style>
