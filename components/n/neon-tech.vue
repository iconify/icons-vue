<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba4wh6eoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba4wh6eoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:neon-tech" /></template>
