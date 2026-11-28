<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn652xb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn652xb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-sparkle-solid" /></template>
