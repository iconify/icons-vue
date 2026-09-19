<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4ni3-bvv.css';
import '../../css/a/amfm1tp9u.css';
import '../../css/e/ey_mdybwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="z4ni3-bvv"/><path class="amfm1tp9u"/><path class="ey_mdybwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:server" /></template>
