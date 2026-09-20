<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvd_6vbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvd_6vbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:visualstudio" /></template>
