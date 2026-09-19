<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dedff8bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dedff8bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xbc" /></template>
