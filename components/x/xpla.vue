<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbv36tbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xpla" /></template>
<style>
.pbv36tbqm {
  fill: var(--svg-color--00b1ff, #00b1ff);
  d: path("m14.052 13.02l-1.014 1.008l6.948 6.954L21 19.968l-6.948-6.954zM4.008 3L3 4.014l6.948 6.948l1.008-1.008zm15.966.012l-6.936 6.96l1.008 1.008l6.942-6.96zM9.966 13.032l-6.942 6.96L4.032 21l6.948-6.96z");
}

</style>
