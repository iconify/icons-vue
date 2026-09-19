<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zx_glyhpr.css';
import '../../css/l/lse2-h-0g.css';
import '../../css/m/mlsnkzbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="zx_glyhpr"/><rect class="lse2-h-0g"/><rect class="mlsnkzbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:reports-solid" /></template>
