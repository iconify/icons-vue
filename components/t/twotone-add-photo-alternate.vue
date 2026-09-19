<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6cz72b_t"/><path class="wbwbx43kg"/><path class="ewvr9nuki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-photo-alternate" /></template>
<style>
.ewvr9nuki {
  fill: currentColor;
  d: path("M20 4V1h-2v3h-3v2h3v2.99h2V6h3V4zm-2 16H4V6h10V4H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V10h-2z");
}

.q6cz72b_t {
  fill: currentColor;
  d: path("m10.21 16.83l-1.96-2.36L5.5 18h11l-3.54-4.71z");
}

.wbwbx43kg {
  fill: currentColor;
  d: path("M16.5 18h-11l2.75-3.53l1.96 2.36l2.75-3.54zM17 7h-3V6H4v14h14V10h-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
