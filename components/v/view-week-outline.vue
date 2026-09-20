<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndq79cc0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndq79cc0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-week-outline" /></template>
