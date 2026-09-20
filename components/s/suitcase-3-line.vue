<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2c3ygb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2c3ygb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:suitcase-3-line" /></template>
