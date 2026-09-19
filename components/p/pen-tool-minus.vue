<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p9pv0vbyl.css';
import '../../css/f/fxex-8b8d.css';
import '../../css/g/g2bflsbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9pv0vbyl"/><path class="fxex-8b8d"/><path class="g2bflsbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pen-tool-minus" /></template>
