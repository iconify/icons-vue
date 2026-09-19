<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4_6nhbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1728};
const content = `<path class="y4_6nhbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:recycle" /></template>
