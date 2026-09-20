<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvi5y0blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvi5y0blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:oil-level" /></template>
