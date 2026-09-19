<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4b-u4sic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4b-u4sic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:string-integer" /></template>
