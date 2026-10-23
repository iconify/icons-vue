<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzhp5pbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzhp5pbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wind-arrow-down" /></template>
