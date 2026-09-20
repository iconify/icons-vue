<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojs3iy_9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojs3iy_9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-up-left-sharp" /></template>
