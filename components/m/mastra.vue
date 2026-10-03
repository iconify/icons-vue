<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsjky8-vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":429.02,"height":429.02,"left":116,"top":34.49};
const content = `<path class="dsjky8-vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mastra" /></template>
