<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whq-7tb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whq-7tb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:mathematics" /></template>
