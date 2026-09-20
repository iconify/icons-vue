<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wigscmbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wigscmbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scorpio-fill" /></template>
