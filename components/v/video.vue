<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r5_qsukyp.css';
import '../../css/f/fi71x7bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":37,"height":32};
const content = `<g class="cuyn6tgcc"><path class="r5_qsukyp"/><path class="fi71x7bwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:video" /></template>
