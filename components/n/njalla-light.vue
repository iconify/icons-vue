<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqr8whb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqr8whb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:njalla-light" /></template>
