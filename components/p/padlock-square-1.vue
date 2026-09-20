<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiazbsqdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiazbsqdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:padlock-square-1" /></template>
