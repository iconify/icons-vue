<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jbl2780ei.css';
import '../../css/b/b92jcf1lx.css';
import '../../css/m/mc1f7e0hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jbl2780ei"/><path clip-rule="evenodd" class="b92jcf1lx"/><path clip-rule="evenodd" class="mc1f7e0hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:turntable-duotone" /></template>
