<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1_a5hbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e1_a5hbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-data" /></template>
