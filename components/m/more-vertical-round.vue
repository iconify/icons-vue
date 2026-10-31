<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i82rs5bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i82rs5bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-vertical-round" /></template>
