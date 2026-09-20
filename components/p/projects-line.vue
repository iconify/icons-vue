<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd7r44bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd7r44bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:projects-line" /></template>
