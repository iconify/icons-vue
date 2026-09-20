<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-0vpold"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strk" /></template>
<style>
.qu-0vpold {
  fill: var(--svg-color--277fe3, #277fe3);
  d: path("M12 10.105V3L6.316 13.895H12V21l5.684-10.895z");
}

</style>
