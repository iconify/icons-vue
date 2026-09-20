<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d48z85b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d48z85b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:menu" /></template>
