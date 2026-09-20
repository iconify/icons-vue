<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-a1b2bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-a1b2bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:torizon" /></template>
