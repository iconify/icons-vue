<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xerd42b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xerd42b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-clock" /></template>
