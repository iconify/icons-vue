<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d97ksobub.css';
import '../../css/z/zepzk2bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d97ksobub"/><path class="zepzk2bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunset-20" /></template>
