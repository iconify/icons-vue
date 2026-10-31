<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgpq7zwwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgpq7zwwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-round" /></template>
