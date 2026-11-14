<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr5hvsl7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hr5hvsl7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ollama-dark" /></template>
