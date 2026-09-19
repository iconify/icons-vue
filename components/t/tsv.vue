<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je3uw7zuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="je3uw7zuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tsv" /></template>
