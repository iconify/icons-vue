<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkzas_28k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkzas_28k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:message-processing" /></template>
