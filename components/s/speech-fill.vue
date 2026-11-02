<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8cnq60ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8cnq60ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speech-fill" /></template>
