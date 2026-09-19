<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lxpifw6tl.css';
import '../../css/j/jsjpbvb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path class="lxpifw6tl"/><path class="jsjpbvb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:perl" /></template>
