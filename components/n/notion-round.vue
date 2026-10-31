<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqxdm0s5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqxdm0s5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notion-round" /></template>
