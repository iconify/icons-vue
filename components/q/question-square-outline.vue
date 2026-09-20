<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jo1mwyf2n.css';
import '../../css/j/jwj5s6brs.css';
import '../../css/l/lle3kpb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jo1mwyf2n"/><path class="jwj5s6brs"/><path clip-rule="evenodd" class="lle3kpb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-square-outline" /></template>
