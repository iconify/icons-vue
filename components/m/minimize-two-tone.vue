<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o38zo9b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o38zo9b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minimize-two-tone" /></template>
