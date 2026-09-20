<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yykgeqaec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yykgeqaec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:map" /></template>
