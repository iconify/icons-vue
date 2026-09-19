<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw9y56b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="zw9y56b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:university" /></template>
