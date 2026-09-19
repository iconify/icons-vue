<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta3fb838w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ta3fb838w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sunrise" /></template>
