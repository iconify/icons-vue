<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9-rlac8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9-rlac8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-heart-outline" /></template>
