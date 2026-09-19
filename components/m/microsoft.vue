<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/druj465fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="druj465fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:microsoft" /></template>
