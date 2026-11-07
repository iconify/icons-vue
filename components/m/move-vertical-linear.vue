<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_d_ntx3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_d_ntx3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-linear" /></template>
