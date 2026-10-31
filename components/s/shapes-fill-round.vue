<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lka41ng8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lka41ng8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-fill-round" /></template>
