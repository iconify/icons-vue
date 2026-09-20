<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6419mrrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6419mrrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ticket-2-line" /></template>
