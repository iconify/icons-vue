<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfknu2blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfknu2blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:oven-mitts-minimalistic-bold" /></template>
