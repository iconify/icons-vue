<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_dek8wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_dek8wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-network-off" /></template>
