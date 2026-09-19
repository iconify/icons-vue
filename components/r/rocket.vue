<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3wq8n-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s3wq8n-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:rocket" /></template>
