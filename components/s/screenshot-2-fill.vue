<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3wy_59gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3wy_59gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:screenshot-2-fill" /></template>
