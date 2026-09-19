<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe89p6bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe89p6bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:volume" /></template>
