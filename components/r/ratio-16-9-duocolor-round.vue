<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej9n68bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej9n68bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-16-9-duocolor-round" /></template>
