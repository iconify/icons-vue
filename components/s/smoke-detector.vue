<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkrcpbcwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkrcpbcwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoke-detector" /></template>
