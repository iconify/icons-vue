<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7-0qs29e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7-0qs29e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:markdownlint" /></template>
