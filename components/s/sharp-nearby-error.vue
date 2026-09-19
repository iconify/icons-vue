<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blk4ptbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-nearby-error" /></template>
<style>
.blk4ptbfs {
  fill: currentColor;
  d: path("M12 7.58L16.42 12L12 16.42L7.58 12zm0 11.62L4.8 12L12 4.8l6 6V7.17l-5.99-5.99L1.18 12.01l10.83 10.83L18 16.83V13.2zm8 .8h2v2h-2zm2-10h-2v8h2z");
}

</style>
