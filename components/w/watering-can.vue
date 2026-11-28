<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbqwwac-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbqwwac-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:watering-can" /></template>
