<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7-6hbkwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-6hbkwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:racing-helmet" /></template>
