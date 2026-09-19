<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhdj6ccwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhdj6ccwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:perform-action" /></template>
