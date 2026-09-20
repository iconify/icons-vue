<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzo92ltrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzo92ltrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-shield-2-line" /></template>
