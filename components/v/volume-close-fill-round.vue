<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omt5egbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omt5egbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-fill-round" /></template>
