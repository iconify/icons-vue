<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x_4i1x07g.css';
import '../../css/z/z0aeb7bio.css';
import '../../css/e/e3livhuwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x_4i1x07g"/><path class="z0aeb7bio"/><path class="e3livhuwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:user-question-mark" /></template>
