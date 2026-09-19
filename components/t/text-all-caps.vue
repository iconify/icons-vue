<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f26vo10au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f26vo10au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-all-caps" /></template>
