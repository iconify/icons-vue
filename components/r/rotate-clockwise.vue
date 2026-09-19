<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx5qtx73f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5qtx73f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-clockwise" /></template>
