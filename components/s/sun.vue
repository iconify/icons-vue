<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4ttxibch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4ttxibch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sun" /></template>
