<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na7l5acoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na7l5acoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reflect-horizontal-alt" /></template>
