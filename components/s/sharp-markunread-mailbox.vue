<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o88bg8bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-markunread-mailbox" /></template>
<style>
.o88bg8bub {
  fill: currentColor;
  d: path("M22 6H10v6H8V4h6V0H6v6H2v16h20z");
}

</style>
