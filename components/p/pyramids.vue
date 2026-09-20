<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8z2b9b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j8z2b9b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pyramids" /></template>
