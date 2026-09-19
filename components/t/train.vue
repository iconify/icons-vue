<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh3nt46sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mh3nt46sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train" /></template>
