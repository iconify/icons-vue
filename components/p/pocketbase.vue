<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wnqhvtd5s.css';
import '../../css/k/k_ru2ibrc.css';
import '../../css/c/cusnesbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path class="wnqhvtd5s"/><path class="k_ru2ibrc"/><path class="cusnesbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pocketbase" /></template>
