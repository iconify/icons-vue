<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2858ac-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2858ac-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:teespring" /></template>
