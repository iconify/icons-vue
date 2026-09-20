<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1qdr1bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1qdr1bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-outline" /></template>
