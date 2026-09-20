<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f841agbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f841agbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tiktok-16" /></template>
