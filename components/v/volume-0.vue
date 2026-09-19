<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d354bab3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d354bab3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:volume-0" /></template>
