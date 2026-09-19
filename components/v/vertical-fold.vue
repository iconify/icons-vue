<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f44evnslo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f44evnslo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vertical-fold" /></template>
