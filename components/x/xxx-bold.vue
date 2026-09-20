<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p5w9n4rnd.css';
import '../../css/f/ft-uu_ism.css';
import '../../css/r/rm1d8ubpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p5w9n4rnd"/><path class="ft-uu_ism"/><path class="rm1d8ubpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:xxx-bold" /></template>
