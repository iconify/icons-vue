<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-6iy7wzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-6iy7wzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:quote-right" /></template>
