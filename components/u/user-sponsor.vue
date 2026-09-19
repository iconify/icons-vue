<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4uribag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ov4uribag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-sponsor" /></template>
