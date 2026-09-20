<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq0o3obze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq0o3obze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ray-start-end" /></template>
