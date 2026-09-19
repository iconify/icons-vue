<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-9fcbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ie-9fcbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:processing-wordmark" /></template>
