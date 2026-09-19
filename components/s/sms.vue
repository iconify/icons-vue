<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20--1bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h20--1bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sms" /></template>
