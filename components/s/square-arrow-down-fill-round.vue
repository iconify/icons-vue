<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2-d67nmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-d67nmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-fill-round" /></template>
