<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps8nv3bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps8nv3bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:timeline-line" /></template>
