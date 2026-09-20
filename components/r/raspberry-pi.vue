<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc0eu1bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fc0eu1bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:raspberry-pi" /></template>
