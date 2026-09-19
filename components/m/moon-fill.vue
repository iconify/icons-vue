<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meg5cxbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="meg5cxbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:moon-fill" /></template>
