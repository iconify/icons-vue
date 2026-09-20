<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvbeo8bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvbeo8bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-check-solid" /></template>
