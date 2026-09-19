<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lddcv2bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lddcv2bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:mandalorian" /></template>
