<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de36oebrp"/><path class="y4y93qy5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-system-update" /></template>
<style>
.de36oebrp {
  fill: currentColor;
  d: path("M7 19h10V5H7zm4-6V8h2v5h3l-4 4l-4-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y4y93qy5c {
  fill: currentColor;
  d: path("M16 13h-3V8h-2v5H8l4 4zm1-11.99L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 19H7V5h10z");
}

</style>
