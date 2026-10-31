<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-xsqfb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-xsqfb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-fill-round" /></template>
