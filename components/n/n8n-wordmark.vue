<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bki3sv5ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="bki3sv5ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:n8n-wordmark" /></template>
