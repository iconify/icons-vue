<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfzarh7wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfzarh7wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-2-fill" /></template>
