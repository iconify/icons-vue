<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8k_y-jda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8k_y-jda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:whatsapp-fill-round" /></template>
