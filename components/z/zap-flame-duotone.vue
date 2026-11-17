<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ior-xybur"/><path class="j9hl2kefd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ior-xybur {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9.417 11.333l-2.502 3.145a.23.23 0 0 1-.259.075a.23.23 0 0 1-.156-.22V11a.667.667 0 0 0-.667-.667H3.667a.32.32 0 0 1-.252-.521l5.003-6.29a.232.232 0 0 1 .415.145V7c0 .368.299.667.667.667h2.167a.32.32 0 0 1 .289.182a.32.32 0 0 1-.038.339ZM17 9c.331 1.653 1.335 3.001 2.667 4C20.742 14.077 21 15.534 21 17a4 4 0 0 1-8 0c0-.682.166-1.499.667-2a1.333 1.333 0 0 0 2.666 0c0-1-.333-1.333-.666-2c-.817-1.635.037-2.962 1.333-4");
}

.j9hl2kefd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.417 11.333l2.501-3.145a.322.322 0 0 0-.251-.521H9.5A.667.667 0 0 1 8.833 7V3.667a.233.233 0 0 0-.415-.145l-5.003 6.29a.322.322 0 0 0 .252.521h2.166c.369 0 .667.299.667.667v3.333c0 .22.278.318.415.145zM17 9c.333 1.667 1.333 3 2.667 4c1 1 1.333 2.333 1.333 4a4 4 0 1 1-8 0c0-1 .333-1.667.667-2m0 0a1.333 1.333 0 1 0 2.666 0c0-1-.333-1.333-.666-2C15 11.667 15.333 10.333 17 9");
}

</style>
