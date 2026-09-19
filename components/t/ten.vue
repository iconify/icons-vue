<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqf8rbc7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yqf8rbc7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ten" /></template>
