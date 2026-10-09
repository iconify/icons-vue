<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh27wbbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uh27wbbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tornado-20-bold" /></template>
