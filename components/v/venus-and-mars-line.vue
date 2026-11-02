<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3e5qfvtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3e5qfvtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:venus-and-mars-line" /></template>
