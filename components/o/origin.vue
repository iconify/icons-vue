<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1b_5fjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1b_5fjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:origin" /></template>
