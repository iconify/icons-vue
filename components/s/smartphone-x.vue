<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg4d5_3hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4d5_3hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-x" /></template>
