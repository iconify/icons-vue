<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l40035c0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l40035c0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sliders-vertical" /></template>
