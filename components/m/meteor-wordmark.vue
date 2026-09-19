<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5o3i-b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z5o3i-b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:meteor-wordmark" /></template>
