<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi135vefz.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/v/v2khsxths.css';
import '../../css/d/dkzresbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mi135vefz"/><g class="jn8qy4bru"><path class="v2khsxths"/><path class="dkzresbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:waving-hand" /></template>
