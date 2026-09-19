<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1-t48yyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1-t48yyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:string-text" /></template>
