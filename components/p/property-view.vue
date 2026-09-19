<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/znqi52bou.css';
import '../../css/j/ju6djclts.css';
import '../../css/r/rsp6aac3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znqi52bou"/><path class="ju6djclts"/><path class="rsp6aac3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:property-view" /></template>
