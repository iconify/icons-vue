<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm5emubfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm5emubfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:parallelogram" /></template>
