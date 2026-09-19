<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8advlwls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b f8advlwls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-distort" /></template>
