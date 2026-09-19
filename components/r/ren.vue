<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi3sprbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vi3sprbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ren" /></template>
