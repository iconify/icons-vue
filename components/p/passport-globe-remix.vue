<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm5jskbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm5jskbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:passport-globe-remix" /></template>
