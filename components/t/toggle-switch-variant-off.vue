<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9pj3mbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9pj3mbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toggle-switch-variant-off" /></template>
