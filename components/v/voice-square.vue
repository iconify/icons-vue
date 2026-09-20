<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4dlu5vmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dlu5vmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:voice-square" /></template>
