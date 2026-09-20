<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r84fri8yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r84fri8yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paint" /></template>
