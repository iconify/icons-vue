<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihwhwwz8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihwhwwz8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-21-9-round" /></template>
