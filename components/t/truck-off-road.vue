<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4e7c1v5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4e7c1v5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-off-road" /></template>
