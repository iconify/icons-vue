<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vecvimbom.css';
import '../../css/f/fd5vhobon.css';
import '../../css/i/ik9h6uvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vecvimbom"/><path class="fd5vhobon"/><path class="ik9h6uvfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-sharp-duotone" /></template>
