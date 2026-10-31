<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm9w6ccmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm9w6ccmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-plus-corner-round" /></template>
