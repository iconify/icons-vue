<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr7o7gxzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr7o7gxzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-dashboard" /></template>
