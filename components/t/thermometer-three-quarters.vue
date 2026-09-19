<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmkuarf1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="tmkuarf1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thermometer-three-quarters" /></template>
