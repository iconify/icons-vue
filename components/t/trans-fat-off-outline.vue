<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba9b20lou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9b20lou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trans-fat-off-outline" /></template>
