<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr7xv9bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="cr7xv9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tablet" /></template>
