<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooxeae80k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ooxeae80k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-left-outline" /></template>
