<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7r-q4bef.css';
import '../../css/k/k-aete30d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7r-q4bef"/><path class="k-aete30d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:restaurant-fine" /></template>
