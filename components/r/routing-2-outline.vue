<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u4jda1b4y.css';
import '../../css/c/cdl2a1bbr.css';
import '../../css/r/rqfiu97ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u4jda1b4y"/><path class="cdl2a1bbr"/><path clip-rule="evenodd" class="rqfiu97ew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-2-outline" /></template>
