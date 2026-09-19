<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghm6t940e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghm6t940e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-flash" /></template>
