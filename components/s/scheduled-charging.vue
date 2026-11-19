<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/tdgve6hdl.css';
import '../../css/r/rvxs6mbfh.css';
import '../../css/y/yxq0mnbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tdgve6hdl"/><path class="rvxs6mbfh"/><path class="yxq0mnbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:scheduled-charging" /></template>
