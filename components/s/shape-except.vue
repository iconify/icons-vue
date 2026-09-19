<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2lsh0bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2lsh0bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shape-except" /></template>
