<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwl7ukh2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwl7ukh2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sail-boat" /></template>
