<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j91vxv8id.css';
import '../../css/v/vgqf9ebff.css';
import '../../css/h/hjpx-0bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="j91vxv8id"/><path class="vgqf9ebff"/><path class="hjpx-0bmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:paper-bitcoin-outline" /></template>
