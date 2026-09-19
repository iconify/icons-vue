<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5iy1lbov"/><path class="rb5qyabay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-nature" /></template>
<style>
.c5iy1lbov {
  fill: currentColor;
  d: path("M12.17 4.17c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.25-5-5-5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rb5qyabay {
  fill: currentColor;
  d: path("M19.17 9.17c0-3.87-3.13-7-7-7s-7 3.13-7 7A6.98 6.98 0 0 0 11 16.06V20H5v2h14v-2h-6v-3.88h-.03c3.49-.4 6.2-3.36 6.2-6.95m-7 5c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.25 5-5 5");
}

</style>
