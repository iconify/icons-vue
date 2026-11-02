<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os70hog4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os70hog4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-up-fill" /></template>
