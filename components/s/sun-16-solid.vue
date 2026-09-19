<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hptyw3s8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hptyw3s8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sun-16-solid" /></template>
