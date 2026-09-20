<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oygjb2btm.css';
import '../../css/w/wf82r5bjl.css';
import '../../css/v/vm6fd7g8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oygjb2btm"/><path class="wf82r5bjl"/><path clip-rule="evenodd" class="vm6fd7g8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-bug3-duotone" /></template>
