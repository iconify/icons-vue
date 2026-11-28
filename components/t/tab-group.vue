<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dzfiyxf4x.css';
import '../../css/n/n0yvt0bhv.css';
import '../../css/y/yljxuhu5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dzfiyxf4x"/><path class="n0yvt0bhv"/><path class="yljxuhu5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tab-group" /></template>
