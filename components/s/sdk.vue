<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3hhpg6el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3hhpg6el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sdk" /></template>
