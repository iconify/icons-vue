<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o8xly4bvt.css';
import '../../css/k/k2g46cqvf.css';
import '../../css/f/fo2bbhb7n.css';
import '../../css/h/hok9940vc.css';
import '../../css/d/dzoymkbbe.css';
import '../../css/g/gz3je7b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="o8xly4bvt"/><path class="k2g46cqvf"/><path clip-rule="evenodd" class="fo2bbhb7n"/><path class="hok9940vc"/><path class="dzoymkbbe"/><path clip-rule="evenodd" class="gz3je7b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:motorcycle" /></template>
