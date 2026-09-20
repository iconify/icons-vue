<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mdb-6xbip.css';
import '../../css/w/wf82r5bjl.css';
import '../../css/y/yjr_673tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mdb-6xbip"/><path class="wf82r5bjl"/><path clip-rule="evenodd" class="yjr_673tk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-plus3-duotone" /></template>
