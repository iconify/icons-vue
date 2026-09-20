<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv8-u4bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8-u4bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-next-outline" /></template>
