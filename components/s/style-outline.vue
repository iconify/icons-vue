<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0f5rt5bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0f5rt5bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:style-outline" /></template>
