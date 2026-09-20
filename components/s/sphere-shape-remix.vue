<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfa8sx9at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfa8sx9at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sphere-shape-remix" /></template>
