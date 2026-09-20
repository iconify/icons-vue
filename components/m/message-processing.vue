<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5kl43b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5kl43b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-processing" /></template>
