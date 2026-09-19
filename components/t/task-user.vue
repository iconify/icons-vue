<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysbo-7bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysbo-7bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-user" /></template>
