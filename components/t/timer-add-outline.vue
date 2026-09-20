<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb47mabsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb47mabsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-add-outline" /></template>
