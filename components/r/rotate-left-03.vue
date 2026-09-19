<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-p95b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-p95b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-left-03" /></template>
