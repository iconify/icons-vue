<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zg3proamv.css';
import '../../css/p/p7aq10b2c.css';
import '../../css/r/ryluzc2qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zg3proamv"/><path class="p7aq10b2c"/><path class="ryluzc2qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:three-squares-line-duotone" /></template>
