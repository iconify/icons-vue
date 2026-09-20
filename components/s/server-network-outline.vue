<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdh0wop_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdh0wop_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-network-outline" /></template>
