<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gom_4pbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oxen" /></template>
<style>
.gom_4pbjc {
  fill: var(--svg-color--12c6ba, #12c6ba);
  fill-rule: evenodd;
  d: path("M12 12L3 4.2h18zm0 0l-9 7.8h18z");
}

</style>
