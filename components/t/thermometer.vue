<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmz8bn8eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmz8bn8eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:thermometer" /></template>
