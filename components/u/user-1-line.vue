<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqod7_waq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqod7_waq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-1-line" /></template>
