<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk4txkbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk4txkbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-left" /></template>
