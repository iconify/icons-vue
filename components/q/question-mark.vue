<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkawcw3ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkawcw3ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:question-mark" /></template>
