<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evqb2ybga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evqb2ybga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-2g" /></template>
