<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ediyy5vvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ediyy5vvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:skew" /></template>
