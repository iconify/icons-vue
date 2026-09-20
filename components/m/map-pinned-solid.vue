<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kc33thgni.css';
import '../../css/l/lg07v2bfn.css';
import '../../css/h/h_pvdzb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kc33thgni"/><path class="lg07v2bfn"/><path class="h_pvdzb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pinned-solid" /></template>
