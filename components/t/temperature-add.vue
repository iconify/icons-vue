<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m67r0olii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m67r0olii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature-add" /></template>
