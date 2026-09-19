<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyjefyu5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nyjefyu5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pie-single" /></template>
