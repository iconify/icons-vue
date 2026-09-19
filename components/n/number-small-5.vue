<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew8w2puiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ew8w2puiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-5" /></template>
