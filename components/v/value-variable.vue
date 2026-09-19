<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opxh7ab4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="opxh7ab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:value-variable" /></template>
