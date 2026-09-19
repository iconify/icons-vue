<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isej-pbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1408};
const content = `<path class="isej-pbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort" /></template>
