<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi16mqriy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi16mqriy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-7-box-multiple" /></template>
