<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu-hdfbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-hdfbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:virus-round" /></template>
