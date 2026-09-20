<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2-1tbeio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2-1tbeio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tv-2-fill" /></template>
