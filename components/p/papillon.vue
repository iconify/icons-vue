<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjasns2tp"/><path class="t4i9xbzsd"/><path class="lx02ojbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:papillon" /></template>
<style>
.cjasns2tp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.285 30.198c-2.682 7.428-6.742 12.797-9.07 11.991c-2.327-.805-2.04-7.479.642-14.907s6.742-12.796 9.07-11.991c2.327.805 2.04 7.479-.642 14.907");
}

.lx02ojbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.175 17.895c7.368 1.088 12.771 4.67 12.068 8c-.702 3.329-7.245 5.146-14.613 4.057s-12.771-4.67-12.068-8c.702-3.33 7.245-5.146 14.613-4.057");
}

.t4i9xbzsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.307 12.675c4.53 5.666 5.809 12.101 2.857 14.372c-2.952 2.272-9.017-.48-13.546-6.147c-4.53-5.667-5.809-12.102-2.857-14.373s9.017.481 13.546 6.148");
}

</style>
