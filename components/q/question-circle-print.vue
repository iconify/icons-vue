<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o7dafxbyv.css';
import '../../css/w/w7sg7srhp.css';
import '../../css/e/e_5r6zbgz.css';
import '../../css/n/nijapbwkt.css';
import '../../css/c/chy-6cb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="o7dafxbyv"/><path class="w7sg7srhp"/><path clip-rule="evenodd" class="e_5r6zbgz"/><path clip-rule="evenodd" class="nijapbwkt"/><path clip-rule="evenodd" class="chy-6cb0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:question-circle-print" /></template>
