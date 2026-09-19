<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef3j2cb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ef3j2cb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pentagon-right-solid" /></template>
