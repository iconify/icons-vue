<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk-0a1bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk-0a1bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:power" /></template>
