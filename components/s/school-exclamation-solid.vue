<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dnlxmdbpb.css';
import '../../css/h/hgu6t-beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dnlxmdbpb"/><path clip-rule="evenodd" class="hgu6t-beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-exclamation-solid" /></template>
