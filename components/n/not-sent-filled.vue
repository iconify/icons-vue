<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tile2lekl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tile2lekl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:not-sent-filled" /></template>
