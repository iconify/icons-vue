<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws8ax8b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws8ax8b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-point-plus" /></template>
