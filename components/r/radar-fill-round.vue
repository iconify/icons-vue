<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnh-q7bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnh-q7bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radar-fill-round" /></template>
