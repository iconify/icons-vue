<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lvr5yhz0c"/><path class="iveo0bcna"/><path class="rg-mz0b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:video-creator" /></template>
<style>
.iveo0bcna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.083 21.166v-4.432h36.502v4.432zm15.494-4.198l-3.964 3.965m11.673-3.965l-3.965 3.965m11.673-3.965l-3.965 3.965M6.083 16.734l-.668-4.382L41.5 6.849l.668 4.381zm10.835-5.98l4.377 3.504m3.243-4.666l4.377 3.503m3.243-4.665l4.377 3.503");
}

.lvr5yhz0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.585 21.166v17.44a2.54 2.54 0 0 1-2.535 2.545H8.629a2.54 2.54 0 0 1-2.546-2.534V21.166m2.985 4.264H39.6M9.068 33.27H39.6M9.068 37.198H39.6M18.738 25.633v7.485m11.192-7.485v7.485");
}

.rg-mz0b9g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.97 17.9c.416 0 .75.335.75.75a.75.75 0 0 1-1.5 0c0-.415.335-.75.75-.75m-.525-4.83a.75.75 0 0 1 .226 1.483a.75.75 0 0 1-.226-1.483");
}

</style>
