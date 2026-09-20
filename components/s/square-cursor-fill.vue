<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3bx3-nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ye3bx3-nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-cursor-fill" /></template>
