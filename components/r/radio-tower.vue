<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsruq6fcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsruq6fcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:radio-tower" /></template>
