<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-83obuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6-83obuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zos-partition" /></template>
