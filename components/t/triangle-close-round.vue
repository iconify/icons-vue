<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz0a0j8fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz0a0j8fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-round" /></template>
