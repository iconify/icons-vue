<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhpg8bclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhpg8bclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-check" /></template>
