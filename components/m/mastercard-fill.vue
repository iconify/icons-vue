<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6gd5e7ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6gd5e7ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastercard-fill" /></template>
