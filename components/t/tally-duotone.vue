<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mratxfbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mratxfbzu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-duotone" /></template>
