<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vokcyn7-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vokcyn7-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:menu" /></template>
