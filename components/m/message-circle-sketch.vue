<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cwe93ybit.css';
import '../../css/k/k22g0i2az.css';
import '../../css/j/jo6urw9ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cwe93ybit"/><path class="k22g0i2az wm-k"/><path class="jo6urw9ef wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-sketch" /></template>
