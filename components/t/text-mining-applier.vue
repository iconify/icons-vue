<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxlwz1bsp.css';
import '../../css/u/ua6u3wino.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxlwz1bsp"/><path class="ua6u3wino"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-mining-applier" /></template>
