<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edm1jx-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edm1jx-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:presentation-graph-outline" /></template>
