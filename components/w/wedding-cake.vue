<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwe8ukbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1920};
const content = `<path class="uwe8ukbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:wedding-cake" /></template>
