<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skh9tab_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-2};
const content = `<path class="skh9tab_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:undo" /></template>
