<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihohqvbwa.css';
import '../../css/v/vb2fm7crz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ihohqvbwa"/><path class="vb2fm7crz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:wifi" /></template>
