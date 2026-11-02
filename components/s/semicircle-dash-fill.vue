<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djxirsb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djxirsb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:semicircle-dash-fill" /></template>
