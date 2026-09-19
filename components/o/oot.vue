<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4pk15lrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d4pk15lrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:oot" /></template>
