<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm4m64byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm4m64byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:segment" /></template>
