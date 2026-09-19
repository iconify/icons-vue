<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f398k2a7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f398k2a7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:zoo" /></template>
