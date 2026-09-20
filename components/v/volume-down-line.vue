<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh1_5c8zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh1_5c8zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-down-line" /></template>
