<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fusn3hbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fusn3hbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:perspective-less" /></template>
