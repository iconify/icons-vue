<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txzu4-dhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txzu4-dhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scan-fill" /></template>
