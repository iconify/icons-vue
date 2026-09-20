<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qko8cdufg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qko8cdufg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skull-outline" /></template>
