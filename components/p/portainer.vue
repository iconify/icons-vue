<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_x_9bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1_x_9bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:portainer" /></template>
