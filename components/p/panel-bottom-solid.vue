<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk_l8xbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk_l8xbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-bottom-solid" /></template>
