<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nan12mbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nan12mbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ordinal" /></template>
