<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2bxj9bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2bxj9bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nintendo-switch-line" /></template>
