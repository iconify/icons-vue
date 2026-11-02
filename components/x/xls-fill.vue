<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i47kys6fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i47kys6fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xls-fill" /></template>
