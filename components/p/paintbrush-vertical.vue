<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcb8d9bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcb8d9bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paintbrush-vertical" /></template>
