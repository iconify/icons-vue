<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nleslac0f"/><path class="gil2ri6ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-input-component" /></template>
<style>
.gil2ri6ee {
  fill: currentColor;
  d: path("M5 2c0-.55-.45-1-1-1s-1 .45-1 1v4H1v10c0 1.3.84 2.4 2 2.82V23h2v-4.18C6.16 18.4 7 17.3 7 16V6H5zm0 14c0 .55-.45 1-1 1s-1-.45-1-1v-2h2zm0-4H3V8h2zm8-10c0-.55-.45-1-1-1s-1 .45-1 1v4H9v10c0 1.3.84 2.4 2 2.82V23h2v-4.18c1.16-.42 2-1.52 2-2.82V6h-2zm0 14c0 .55-.45 1-1 1s-1-.45-1-1v-2h2zm0-4h-2V8h2zm8-6V2c0-.55-.45-1-1-1s-1 .45-1 1v4h-2v10c0 1.3.84 2.4 2 2.82V23h2v-4.18c1.16-.42 2-1.52 2-2.82V6zm0 10c0 .55-.45 1-1 1s-1-.45-1-1v-2h2zm0-4h-2V8h2z");
}

.nleslac0f {
  fill: currentColor;
  d: path("M11 16c0 .55.45 1 1 1s1-.45 1-1v-2h-2zm-8 0c0 .55.45 1 1 1s1-.45 1-1v-2H3zm16 0c0 .55.45 1 1 1s1-.45 1-1v-2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
