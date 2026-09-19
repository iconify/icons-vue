<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/z80j_teei.css';
import '../../css/e/e7eq51t6z.css';
import '../../css/i/i036dddnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z80j_teei"/><circle class="e7eq51t6z"/><path class="i036dddnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-off-01" /></template>
