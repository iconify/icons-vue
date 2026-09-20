<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alfk40bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alfk40bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stethoscope-line" /></template>
