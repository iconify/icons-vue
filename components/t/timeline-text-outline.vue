<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th-4vjbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th-4vjbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-text-outline" /></template>
