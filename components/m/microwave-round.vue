<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-cdchb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-cdchb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microwave-round" /></template>
