<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/bs1-8-ydm.css';
import '../../css/b/bxyseltqm.css';
import '../../css/u/u78lc2bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="bs1-8-ydm"/><path class="bxyseltqm"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pined-light" /></template>
