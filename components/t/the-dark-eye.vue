<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnvjofq_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnvjofq_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:the-dark-eye" /></template>
