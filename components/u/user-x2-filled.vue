<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dtl23o_xq.css';
import '../../css/l/lpx6j3cwi.css';
import '../../css/b/b30alwicb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="dtl23o_xq"/><path class="lpx6j3cwi"/><path clip-rule="evenodd" class="b30alwicb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-x2-filled" /></template>
