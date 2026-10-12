<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfc93ebce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfc93ebce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-2-filled" /></template>
