<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvky1g0pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvky1g0pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tv-retro" /></template>
