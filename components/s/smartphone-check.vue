<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3ojn9owv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ojn9owv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-check" /></template>
