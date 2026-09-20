<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-g22cfbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="e-g22cfbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:megaphone-1" /></template>
