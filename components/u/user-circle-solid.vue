<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uspk1ccev.css';
import '../../css/m/m4n2s7lvv.css';
import '../../css/n/nu5co54pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uspk1ccev"/><path class="m4n2s7lvv"/><path class="nu5co54pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-circle-solid" /></template>
