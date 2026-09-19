<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg3l_9b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg3l_9b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-graduate-outline" /></template>
