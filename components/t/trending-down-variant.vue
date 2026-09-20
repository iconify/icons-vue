<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rywgoibcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rywgoibcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trending-down-variant" /></template>
