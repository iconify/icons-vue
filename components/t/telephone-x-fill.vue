<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6x4mbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vn6x4mbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-x-fill" /></template>
