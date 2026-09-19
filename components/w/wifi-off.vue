<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk14dmbbe.css';
import '../../css/k/km46x-8as.css';
import '../../css/f/fov68487d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk14dmbbe"/><circle class="km46x-8as"/><path class="fov68487d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:wifi-off" /></template>
