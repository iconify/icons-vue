<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj58hmgby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oj58hmgby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pre" /></template>
