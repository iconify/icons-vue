<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hszfhmbqj"/><path class="fkul_rbne"/><path class="w9vf0cl5w"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mp" /></template>
<style>
.fkul_rbne {
  fill: currentColor;
  d: path("M5 5v14h14V5zm7.5 10H11v-4.5h-1v3H8.5v-3h-1V15H6v-5c0-.55.45-1 1-1h4.5c.55 0 1 .45 1 1zm5.5-2.5c0 .55-.45 1-1 1h-2V15h-1.5V9H17c.55 0 1 .45 1 1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hszfhmbqj {
  fill: currentColor;
  d: path("M15 10.5h1.5V12H15z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jor-usn7v {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2M5 19V5h14v14z");
}

.w9vf0cl5w {
  fill: currentColor;
  d: path("M17 9h-3.5v6H15v-1.5h2c.55 0 1-.45 1-1V10c0-.55-.45-1-1-1m-.5 3H15v-1.5h1.5zm-5-3H7c-.55 0-1 .45-1 1v5h1.5v-4.5h1v3H10v-3h1V15h1.5v-5c0-.55-.45-1-1-1");
}

</style>
