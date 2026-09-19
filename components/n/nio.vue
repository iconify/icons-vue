<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9976bbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z9976bbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nio" /></template>
