<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jssfmibdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jssfmibdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tooltips-2-line" /></template>
