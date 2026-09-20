<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8hwbvb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8hwbvb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:snowflake" /></template>
