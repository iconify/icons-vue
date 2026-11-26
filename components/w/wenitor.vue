<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xknpqhb_d.css';
import '../../css/e/eu8dnzbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="xknpqhb_d"/><path class="eu8dnzbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wenitor" /></template>
