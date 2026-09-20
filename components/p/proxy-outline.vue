<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbrq54brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbrq54brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:proxy-outline" /></template>
