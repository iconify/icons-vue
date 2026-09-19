<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ox-7crkhe.css';
import '../../css/x/x-797_g3v.css';
import '../../css/g/g1gju2brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ox-7crkhe"/><path class="x-797_g3v"/><path clip-rule="evenodd" class="g1gju2brq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:trash" /></template>
