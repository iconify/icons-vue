<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq1jstb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq1jstb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-round" /></template>
