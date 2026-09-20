<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4lumlb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4lumlb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-marker" /></template>
