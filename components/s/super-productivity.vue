<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dinz6tf1u.css';
import '../../css/y/y5-o4cbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dinz6tf1u"/><path class="y5-o4cbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:super-productivity" /></template>
