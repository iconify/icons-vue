<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysa-polzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysa-polzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:palette-line" /></template>
