<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4d2-453k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4d2-453k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:peanut-off" /></template>
