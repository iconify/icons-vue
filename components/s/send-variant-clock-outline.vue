<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rld3_rbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rld3_rbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-variant-clock-outline" /></template>
