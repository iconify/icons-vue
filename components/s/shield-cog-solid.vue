<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5o7o8bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5o7o8bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-cog-solid" /></template>
