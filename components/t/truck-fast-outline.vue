<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tylc5dbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tylc5dbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-fast-outline" /></template>
