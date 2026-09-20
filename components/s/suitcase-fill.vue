<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h78-_kb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h78-_kb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:suitcase-fill" /></template>
