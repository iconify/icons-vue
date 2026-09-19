<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us3jq0bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="us3jq0bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sunrise" /></template>
