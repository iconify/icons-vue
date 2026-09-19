<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a75cpub2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a75cpub2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:tailwind-css" /></template>
