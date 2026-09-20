<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wakm7qbwd"/><path class="zku_72oen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:no-entry" /></template>
<style>
.wakm7qbwd {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18");
}

.zku_72oen {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 20a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2z");
}

</style>
