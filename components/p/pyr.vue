<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtgZ8zcmI)" clip-rule="evenodd" class="zsk_rcc7h"/><defs><linearGradient id="SVGtgZ8zcmI" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ymxfq5byl"/><stop offset="1" class="x1kmm4b1e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pyr" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.x1kmm4b1e {
  stop-color: var(--svg-color--ee6233, #ee6233);
}

.ymxfq5byl {
  stop-color: var(--svg-color--fcca08, #fcca08);
}

.zsk_rcc7h {
  fill-rule: evenodd;
  d: path("M12.52 3c.018.36-.225 1.433-1.337 2.837c-.301.381-.646.775-1 1.18C8.906 8.477 7.5 10.085 7.5 11.776c0 1.727.795 2.87 1.193 3.224c.059-.438.448-1.61 1.535-2.79c.334-.364.82-.763 1.347-1.198c1.62-1.333 3.65-3.005 3.026-5.024c0 .52-.395 1.771-1.974 2.615c-1.58.843-2.54 1.87-2.823 2.277c-.036-.196.105-.914.611-1.598l.19-.25c.84-1.104 2.6-3.418 1.915-6.032m-1.04 18c-.017-.36.225-1.433 1.337-2.837c.301-.381.646-.775 1-1.18c1.277-1.46 2.683-3.068 2.683-4.759c0-1.727-.795-2.87-1.193-3.224c-.059.438-.448 1.61-1.535 2.791c-.334.363-.82.762-1.347 1.197c-1.62 1.333-3.65 3.005-3.026 5.024c0-.52.395-1.771 1.974-2.615c1.58-.843 2.54-1.87 2.824-2.277c.035.196-.106.914-.612 1.598l-.19.25c-.84 1.105-2.6 3.418-1.915 6.032");
}

</style>
