<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl8zs6bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8zs6bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spinrilla-logo" /></template>
