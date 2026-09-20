<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcx6nf7bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-1};
const content = `<path class="wcx6nf7bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:move" /></template>
