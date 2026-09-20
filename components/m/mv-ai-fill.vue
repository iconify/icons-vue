<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm33rhd9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm33rhd9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mv-ai-fill" /></template>
