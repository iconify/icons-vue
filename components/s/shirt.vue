<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrqz273dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqz273dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shirt" /></template>
