<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldh3u0amb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldh3u0amb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openai-dark" /></template>
