<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z86c3fbnt"/><path class="c7482hm8x"/><path class="w3j0966ch"/><path class="uch2qk0pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-on-device-training" /></template>
<style>
.c7482hm8x {
  fill: currentColor;
  d: path("M11 16h2v1h-2zm1-5c-1.1 0-2 .9-2 2c0 .74.4 1.38 1 1.72v.78h2v-.78c.6-.35 1-.98 1-1.72c0-1.1-.9-2-2-2");
}

.uch2qk0pi {
  fill: currentColor;
  d: path("M16.01 15.95c.62-.83.99-1.84.99-2.95s-.37-2.12-.99-2.95l-1.07 1.07c.35.54.56 1.19.56 1.88s-.21 1.34-.56 1.88zm-6.95-1.07c-.35-.54-.56-1.19-.56-1.88c0-1.93 1.57-3.5 3.5-3.5v1.25l2.25-2l-2.25-2V8c-2.76 0-5 2.24-5 5c0 1.11.37 2.12.99 2.95z");
}

.w3j0966ch {
  fill: currentColor;
  d: path("M18 1.01L6 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M18 21H6v-1h12zm0-3H6V6h12zm0-14H6V3h12z");
}

.z86c3fbnt {
  fill: currentColor;
  d: path("M6 20h12v1H6zM6 3h12v1H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
