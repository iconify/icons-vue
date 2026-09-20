<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhhe6byck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhhe6byck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:move-expand-vertical-bold" /></template>
