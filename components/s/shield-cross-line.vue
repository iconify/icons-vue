<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg6w64bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg6w64bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-cross-line" /></template>
