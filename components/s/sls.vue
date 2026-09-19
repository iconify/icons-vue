<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmok94b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vmok94b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sls" /></template>
