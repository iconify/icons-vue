<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbasz78dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbasz78dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:truck-fill" /></template>
