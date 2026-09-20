<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azi09o8qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="azi09o8qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wizards-of-the-coast" /></template>
