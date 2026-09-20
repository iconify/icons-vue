<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fnayhz3pu.css';
import '../../css/l/l5f9elzdh.css';
import '../../css/j/j_5sfhbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fnayhz3pu"/><path class="l5f9elzdh"/><path class="j_5sfhbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-line-duotone" /></template>
