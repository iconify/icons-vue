<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txq30yb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plr" /></template>
<style>
.txq30yb0q {
  fill: var(--svg-color--00ff24, #00ff24);
  d: path("M18.188 6.375L14.813 3v11.25h-9v3.375L9.187 21v-3.375h9zM10.313 5.25h-4.5v4.5h4.5z");
}

</style>
