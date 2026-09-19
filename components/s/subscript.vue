<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4jx56bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4jx56bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:subscript" /></template>
