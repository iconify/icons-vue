<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_j650j5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_j650j5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signature-duotone-round" /></template>
