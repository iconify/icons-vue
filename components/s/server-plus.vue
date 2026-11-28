<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6zwwv9sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6zwwv9sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:server-plus" /></template>
