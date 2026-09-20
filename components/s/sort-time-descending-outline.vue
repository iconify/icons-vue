<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qotdusbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qotdusbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-time-descending-outline" /></template>
