<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hhvux2gvb.css';
import '../../css/m/mnaosmbku.css';
import '../../css/z/zrxk0nb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhvux2gvb"/><path class="mnaosmbku"/><path class="zrxk0nb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-recive" /></template>
