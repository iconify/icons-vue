<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrrlvb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whrrlvb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:timer" /></template>
