<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktb81tbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ktb81tbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:warning-filled" /></template>
