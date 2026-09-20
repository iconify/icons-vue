<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bumq7onsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bumq7onsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:read-more-outline" /></template>
