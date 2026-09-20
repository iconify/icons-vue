<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d03my4b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d03my4b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:met" /></template>
