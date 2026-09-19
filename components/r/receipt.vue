<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s8x7i_bes.css';
import '../../css/h/h69o561-p.css';
import '../../css/v/v5qih58fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="s8x7i_bes"/><path class="h69o561-p"/><path class="v5qih58fr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:receipt" /></template>
