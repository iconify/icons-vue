<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylpoqbbdx.css';
import '../../css/k/klf1_rboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ylpoqbbdx"/><path class="klf1_rboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:screen-map" /></template>
