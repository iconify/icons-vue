<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgc8pk4bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgc8pk4bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-variant-clock" /></template>
