<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tton4-8be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tton4-8be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pouch" /></template>
