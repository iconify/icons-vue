<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbvovsrat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sbvovsrat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-tag-outline" /></template>
