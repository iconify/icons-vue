<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c1wmostxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nab" /></template>
<style>
.c1wmostxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.99 24l10.09-4.773l-2.559-10.864l10.022 4.913l6.898-8.775L31.849 15.4l11.161-.078L35.99 24l7.02 8.678l-11.161-.078l-2.408 10.899l-6.898-8.775l-10.022 4.913l2.559-10.864zm26.859-8.6L22.27 26.344m15.441-10.982l-9.777 11.143");
}

</style>
