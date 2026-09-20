<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcwxktbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcwxktbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rhombus-split-outline" /></template>
