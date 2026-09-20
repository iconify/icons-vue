<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev43y730d.css';
import '../../css/y/y-tut6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ev43y730d"/><path class="y-tut6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-snowman" /></template>
