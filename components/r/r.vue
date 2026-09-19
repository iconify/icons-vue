<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at7hvxiod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="at7hvxiod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:r" /></template>
