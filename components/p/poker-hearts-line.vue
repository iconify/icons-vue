<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uie78-bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uie78-bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-hearts-line" /></template>
