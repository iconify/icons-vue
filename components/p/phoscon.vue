<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9en5ccwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9en5ccwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:phoscon" /></template>
