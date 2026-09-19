<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1rssb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km1rssb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:overweight-24px" /></template>
