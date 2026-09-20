<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3o-hk-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h3o-hk-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-wayfinder-stairs-2-stairs-staircase-left" /></template>
