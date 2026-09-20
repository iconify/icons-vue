<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcet0h_kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcet0h_kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pool" /></template>
