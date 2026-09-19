<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1-02ord"/><path class="yw6ay2bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-no-crash" /></template>
<style>
.ei1-02ord {
  fill: currentColor;
  d: path("M5 15v5h14v-5zm2.5 4c-.83 0-1.5-.67-1.5-1.5S6.67 16 7.5 16s1.5.67 1.5 1.5S8.33 19 7.5 19m9 0c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yw6ay2bvk {
  fill: currentColor;
  d: path("M18.92 9.01C18.72 8.42 18.16 8 17.5 8h-11c-.66 0-1.21.42-1.42 1.01L3 15v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8zM6.85 10h10.29l1.04 3H5.81zM19 20H5v-5h14zM6 17.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5S8.33 19 7.5 19S6 18.33 6 17.5m9 0c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5M12 6.36L9.17 3.54l1.41-1.41L12 3.54L15.54 0l1.41 1.41z");
}

</style>
