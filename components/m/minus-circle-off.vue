<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpdbtwz4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpdbtwz4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:minus-circle-off" /></template>
