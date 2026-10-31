<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_olhgb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_olhgb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-check-fill-round" /></template>
