<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xltm0abxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xltm0abxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sun-protection-outline" /></template>
