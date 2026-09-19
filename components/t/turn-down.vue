<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7792ebiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h7792ebiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:turn-down" /></template>
