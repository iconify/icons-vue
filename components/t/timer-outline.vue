<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzif5jboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzif5jboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-outline" /></template>
