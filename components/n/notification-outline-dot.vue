<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8a476e8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8a476e8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification-outline-dot" /></template>
