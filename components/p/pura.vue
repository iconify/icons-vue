<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9-6asbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e9-6asbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pura" /></template>
