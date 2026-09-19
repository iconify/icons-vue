<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tf7tatarv.css';
import '../../css/h/h8x2rylov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tf7tatarv"/><path clip-rule="evenodd" class="h8x2rylov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:outgoing-call-solid" /></template>
