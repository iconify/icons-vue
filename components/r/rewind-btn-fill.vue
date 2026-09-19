<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arq6blbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arq6blbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:rewind-btn-fill" /></template>
