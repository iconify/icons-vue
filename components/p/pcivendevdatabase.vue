<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ak-4r_bbj"/><path class="znrp1kb2i"/><path class="d7jjk7btr"/><path class="mdhkoz9qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pcivendevdatabase" /></template>
<style>
.ak-4r_bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.1 19.05l1.4-.9l-5.9-4.8l-6.1 3.2l-13.5-2.3l-2.9 1.6");
}

.d7jjk7btr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.6 15.05l3.1-1.6l5.9 5.9l-3.5 2.2m3.5-2.2l.1 2.8l-1.9 1.3");
}

.mdhkoz9qf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.7 22.15l4.7 5l-.1 4m-11.8-13.8l3.2-1.8m-1.4 3.9l3.2-2.1m9.7 0l1.2 1.1l-1.4 1l-1.3-1.2Zm9.6-1.2l-2.3 1.3l2 1.8l2.4-1.4Zm-15.2 4l1.1 1.2l1.3-.9l-1.2-1.1Z");
}

.znrp1kb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.3 31.15l2-1.3l-1.6-1.7l6.3-3.9l1.6 1.6l10.5-6.8l-.8-.7m-36.6-1.8l-.2-3.7l2.4-1l16.3 19.2v1.4l1.7 1.7v2l-1.5-1.4l-1.3-.2L7 15.85Zm2.3-.7L6.9 12");
}

</style>
