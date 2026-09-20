<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2bt4rt7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2bt4rt7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:numbers-fill" /></template>
