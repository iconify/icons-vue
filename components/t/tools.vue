<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmval1bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmval1bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tools" /></template>
