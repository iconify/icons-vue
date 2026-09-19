<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivb83k4ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivb83k4ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wind-energy-alt" /></template>
