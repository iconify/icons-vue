<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fza5vnbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fza5vnbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tile-caution-heavy" /></template>
