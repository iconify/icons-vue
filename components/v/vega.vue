<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttcp0zbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vega" /></template>
<style>
.ttcp0zbju {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 3h2.4v13.2H4.5zm4.8 15.6H6.9v-2.4h2.4zm2.4 0V21H9.3v-2.4zm0 0v-2.4h2.4v2.4zm3-15.6h2.4v10.8h-2.4zm2.4 10.8h2.4v2.4h-2.4z");
}

</style>
