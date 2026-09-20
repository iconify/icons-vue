<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uspk1ccev.css';
import '../../css/a/aao2npbao.css';
import '../../css/n/nja63b-rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uspk1ccev"/><path class="aao2npbao"/><path class="nja63b-rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-square-solid" /></template>
