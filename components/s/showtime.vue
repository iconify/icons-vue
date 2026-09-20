<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7aex9hdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7aex9hdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:showtime" /></template>
