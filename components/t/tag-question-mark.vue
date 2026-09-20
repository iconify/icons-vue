<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mn9y2kbuu.css';
import '../../css/a/agy6o3bme.css';
import '../../css/p/pjq09mwpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mn9y2kbuu"/><path class="agy6o3bme"/><path class="pjq09mwpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-question-mark" /></template>
