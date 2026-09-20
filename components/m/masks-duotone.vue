<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lvoecyb6c.css';
import '../../css/m/mhxymalnj.css';
import '../../css/t/teg2gbcuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lvoecyb6c"/><path class="mhxymalnj"/><path class="teg2gbcuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:masks-duotone" /></template>
