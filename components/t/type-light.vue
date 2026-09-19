<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr8kzw2nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr8kzw2nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:type-light" /></template>
