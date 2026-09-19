<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9qyvcbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m9qyvcbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:qsp" /></template>
