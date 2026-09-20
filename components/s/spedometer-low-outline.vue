<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrb4imbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrb4imbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-low-outline" /></template>
