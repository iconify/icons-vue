<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7vf8qkla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7vf8qkla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tea-off" /></template>
