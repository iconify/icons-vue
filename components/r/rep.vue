<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w97qe2lja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w97qe2lja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rep" /></template>
