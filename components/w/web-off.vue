<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvphbztct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvphbztct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:web-off" /></template>
