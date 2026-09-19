<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1dnwv6dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1dnwv6dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-noise" /></template>
