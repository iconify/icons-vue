<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ex8terbtf.css';
import '../../css/j/j5hs9_bth.css';
import '../../css/k/k7pxxab3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ex8terbtf"/><circle class="j5hs9_bth"/><path class="k7pxxab3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pizza-slice-filled" /></template>
