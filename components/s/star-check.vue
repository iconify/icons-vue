<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgljb1bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgljb1bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:star-check" /></template>
