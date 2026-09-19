<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv5jlwbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv5jlwbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volleyball" /></template>
