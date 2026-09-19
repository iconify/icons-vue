<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-3c8_piw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-3c8_piw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:tablet" /></template>
