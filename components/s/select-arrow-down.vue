<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o27827bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o27827bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-arrow-down" /></template>
