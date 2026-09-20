<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug_j8ebhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ug_j8ebhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:north" /></template>
