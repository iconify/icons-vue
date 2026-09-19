<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdq557ezd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tdq557ezd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbs-down-filled" /></template>
