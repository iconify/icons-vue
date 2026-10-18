<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr6-vqfij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr6-vqfij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-2" /></template>
