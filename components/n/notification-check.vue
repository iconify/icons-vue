<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en9bmcc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en9bmcc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:notification-check" /></template>
