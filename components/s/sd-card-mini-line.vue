<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlkquaciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlkquaciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sd-card-mini-line" /></template>
