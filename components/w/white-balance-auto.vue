<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnj14oqzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnj14oqzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:white-balance-auto" /></template>
