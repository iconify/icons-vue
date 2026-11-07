<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ychitgsnk.css';
import '../../css/l/l3o4rbo3n.css';
import '../../css/l/lennyzbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ychitgsnk"/><path class="l3o4rbo3n"/><path class="lennyzbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-record-line-duotone" /></template>
