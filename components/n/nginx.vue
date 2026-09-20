<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv3ktebxk.css';
import '../../css/e/eq1ur8_nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mv3ktebxk"/><path class="eq1ur8_nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nginx" /></template>
