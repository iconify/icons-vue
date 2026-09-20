<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieo4nfb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieo4nfb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:timer-2-line" /></template>
