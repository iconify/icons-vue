<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/doprogbdx.css';
import '../../css/b/b5tmlbjxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="doprogbdx"/><path class="b5tmlbjxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sdl" /></template>
