<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5jl7fbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5jl7fbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-access" /></template>
