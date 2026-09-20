<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aepqf5neu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aepqf5neu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-box-outline" /></template>
