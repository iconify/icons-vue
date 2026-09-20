<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw516dbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw516dbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:pillow" /></template>
