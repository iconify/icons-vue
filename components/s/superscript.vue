<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/beqnu5b5d.css';
import '../../css/g/g4q6mwbtn.css';
import '../../css/x/x036cgb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="beqnu5b5d"/><path class="g4q6mwbtn"/><path class="x036cgb2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:superscript" /></template>
