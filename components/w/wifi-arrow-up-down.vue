<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0zrg5ztm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0zrg5ztm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-arrow-up-down" /></template>
