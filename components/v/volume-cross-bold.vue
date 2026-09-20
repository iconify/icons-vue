<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i8zvzvzkl.css';
import '../../css/o/oxic0dcak.css';
import '../../css/d/dagas5qlh.css';
import '../../css/g/gb7ygw3xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i8zvzvzkl"/><path clip-rule="evenodd" class="oxic0dcak"/><path class="dagas5qlh"/><path class="gb7ygw3xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-cross-bold" /></template>
