<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el9bc6-4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el9bc6-4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mv-ai-line" /></template>
