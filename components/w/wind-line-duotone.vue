<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o9eziwahb.css';
import '../../css/u/uhyb91t7h.css';
import '../../css/e/e1amrgqjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9eziwahb"/><path class="uhyb91t7h"/><path class="e1amrgqjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wind-line-duotone" /></template>
