<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etm1unpln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="etm1unpln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-1" /></template>
