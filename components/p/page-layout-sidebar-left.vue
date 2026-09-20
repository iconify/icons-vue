<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8w928bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8w928bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-layout-sidebar-left" /></template>
