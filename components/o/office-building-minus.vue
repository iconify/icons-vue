<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m73j46bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m73j46bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-minus" /></template>
