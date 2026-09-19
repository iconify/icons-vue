<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8f30sbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8f30sbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:tablet" /></template>
