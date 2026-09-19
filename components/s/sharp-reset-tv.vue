<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-o8v_vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-reset-tv" /></template>
<style>
.ft-o8v_vd {
  fill: currentColor;
  d: path("M22 10h-9.01V7L9 11l3.99 4v-3H20v5H4V5h16v3h2V3H2v16h6v2h8v-2h6z");
}

</style>
