<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4guh2bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4guh2bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transition" /></template>
