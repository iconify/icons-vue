<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuf7-zbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuf7-zbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:toolbox" /></template>
