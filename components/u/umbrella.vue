<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gikp8hi5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gikp8hi5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:umbrella" /></template>
