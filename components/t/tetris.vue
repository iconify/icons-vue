<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykrhbm4ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ykrhbm4ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tetris" /></template>
