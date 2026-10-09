<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shrshrltt.css';
import '../../css/j/jqow3gbkz.css';
import '../../css/e/euu9n8cdz.css';
import '../../css/x/x_1wshpcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="shrshrltt"/><path class="jqow3gbkz"/><path class="euu9n8cdz"/><path class="x_1wshpcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plant-pot-20-bold" /></template>
