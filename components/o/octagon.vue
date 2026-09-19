<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfa6agb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfa6agb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:octagon" /></template>
