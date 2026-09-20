<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy2lz1b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy2lz1b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-right" /></template>
