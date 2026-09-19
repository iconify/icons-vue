<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lkdxq8b7i.css';
import '../../css/h/h5w6q1y6d.css';
import '../../css/t/tf7ojvbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkdxq8b7i"/><circle class="h5w6q1y6d"/><path class="tf7ojvbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swimming" /></template>
