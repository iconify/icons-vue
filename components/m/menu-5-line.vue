<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgb2-fblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgb2-fblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-5-line" /></template>
