<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qtba_comf.css';
import '../../css/g/g9oozz2sw.css';
import '../../css/s/swq3r6bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qtba_comf"/><path clip-rule="evenodd" class="g9oozz2sw"/><path class="swq3r6bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:reddit-solid" /></template>
