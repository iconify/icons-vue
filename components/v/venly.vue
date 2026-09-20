<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGZNatddXb)" class="v_hs5fbbh"/><defs><linearGradient id="SVGZNatddXb" x1="10.265" x2="21.947" y1="3.9" y2="7.16" gradientUnits="userSpaceOnUse"><stop class="bmjwc1blo"/><stop offset="1" class="xmdw4_btk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:venly" /></template>
<style>
.bmjwc1blo {
  stop-color: var(--svg-color--7735e8, #7735e8);
}

.ft5dv1b6b {
  fill: none;
}

.v_hs5fbbh {
  d: path("m20.825 9.206l-2.208.818c-.093.033-.183-.055-.143-.146l2.46-5.826a.11.11 0 0 0-.14-.145l-4.677 1.597a.33.33 0 0 0-.2.187l-3.17 7.801c-.039.099.06.198.16.162l1.98-.708c.11-.038.212.077.153.178l-2.91 4.816a.165.165 0 0 1-.28 0l-2.909-4.818c-.06-.1.04-.217.152-.179l1.98.708c.101.036.2-.063.16-.162L8.062 5.691a.33.33 0 0 0-.2-.187L3.19 3.907c-.092-.03-.177.058-.14.145l2.458 5.826c.036.088-.054.178-.144.146l-2.193-.818c-.113-.041-.214.077-.152.178l6.53 10.549a.36.36 0 0 0 .307.167h4.28a.36.36 0 0 0 .307-.167l6.542-10.549c.054-.101-.047-.22-.16-.178");
}

.xmdw4_btk {
  stop-color: var(--svg-color--c62cf1, #c62cf1);
}

</style>
