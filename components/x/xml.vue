<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-m4umibe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j-m4umibe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:xml" /></template>
