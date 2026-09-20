<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-fc-4aoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-fc-4aoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-horizontal" /></template>
