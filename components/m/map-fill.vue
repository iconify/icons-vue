<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsxtddznh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gsxtddznh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:map-fill" /></template>
