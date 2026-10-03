<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7e39wbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7e39wbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion" /></template>
