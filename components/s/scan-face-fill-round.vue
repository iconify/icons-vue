<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m35f2mb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m35f2mb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-face-fill-round" /></template>
