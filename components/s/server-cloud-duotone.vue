<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jjs64fbrx.css';
import '../../css/q/q1yocybne.css';
import '../../css/o/o3lva51sv.css';
import '../../css/d/dab4yko7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jjs64fbrx"/><path clip-rule="evenodd" class="q1yocybne"/><path class="o3lva51sv"/><path clip-rule="evenodd" class="dab4yko7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-cloud-duotone" /></template>
