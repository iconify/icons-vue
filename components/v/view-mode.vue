<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs8k-2cze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rs8k-2cze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:view-mode" /></template>
