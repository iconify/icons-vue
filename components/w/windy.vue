<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2p6bwb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2p6bwb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:windy" /></template>
