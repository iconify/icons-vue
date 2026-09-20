<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjeu243wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zjeu243wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:underline-u" /></template>
