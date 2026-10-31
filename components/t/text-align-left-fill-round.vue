<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6oh2umiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6oh2umiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-left-fill-round" /></template>
