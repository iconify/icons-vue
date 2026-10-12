<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrai4biei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrai4biei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:slider-fill-20" /></template>
