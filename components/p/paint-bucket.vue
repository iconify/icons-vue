<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv6yotz8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cv6yotz8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:paint-bucket" /></template>
