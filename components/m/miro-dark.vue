<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1yzn8b3d.css';
import '../../css/v/vkrhsz27r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<g class="ft5dv1b6b"><path class="n1yzn8b3d"/><path clip-rule="evenodd" class="vkrhsz27r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:miro-dark" /></template>
