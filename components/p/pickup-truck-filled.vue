<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utcr3yxbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utcr3yxbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pickup-truck-filled" /></template>
