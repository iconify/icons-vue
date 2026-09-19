<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se_do7boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="se_do7boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:people-robbery" /></template>
