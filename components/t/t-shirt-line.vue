<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixjz6bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cixjz6bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:t-shirt-line" /></template>
