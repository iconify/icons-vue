<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5wkwyb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5wkwyb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:perspective-more" /></template>
