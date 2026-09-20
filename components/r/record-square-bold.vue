<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3n_sn-9k.css';
import '../../css/t/t9okf8slh.css';
import '../../css/j/jw3tb4bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r3n_sn-9k"/><path class="t9okf8slh"/><path clip-rule="evenodd" class="jw3tb4bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-square-bold" /></template>
