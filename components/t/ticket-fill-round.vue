<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1zu28dvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1zu28dvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-fill-round" /></template>
