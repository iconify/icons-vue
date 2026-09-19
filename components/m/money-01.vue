<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/esk48yngh.css';
import '../../css/s/sjwyhhial.css';
import '../../css/t/tl_x59b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esk48yngh"/><path class="sjwyhhial"/><path class="tl_x59b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-01" /></template>
