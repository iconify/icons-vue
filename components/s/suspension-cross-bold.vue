<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uqjbkfhng.css';
import '../../css/i/i_xm1xkcl.css';
import '../../css/i/iz7xyshmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uqjbkfhng"/><path class="i_xm1xkcl"/><path class="iz7xyshmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suspension-cross-bold" /></template>
