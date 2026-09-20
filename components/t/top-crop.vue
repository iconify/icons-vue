<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyd0wpb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyd0wpb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:top-crop" /></template>
