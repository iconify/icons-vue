<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru9wcp0zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru9wcp0zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-percent-alert" /></template>
