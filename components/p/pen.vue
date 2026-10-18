<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oty88xbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oty88xbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pen" /></template>
