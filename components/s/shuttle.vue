<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty80g_bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ty80g_bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shuttle" /></template>
