<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6s56hbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6s56hbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-fill" /></template>
