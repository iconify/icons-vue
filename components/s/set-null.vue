<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt3nklbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt3nklbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:set-null" /></template>
