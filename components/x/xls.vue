<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbg6-9b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dbg6-9b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:xls" /></template>
