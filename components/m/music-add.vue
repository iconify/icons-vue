<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfkm__b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vfkm__b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:music-add" /></template>
