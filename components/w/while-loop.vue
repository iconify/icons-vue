<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmci4ixfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmci4ixfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:while-loop" /></template>
