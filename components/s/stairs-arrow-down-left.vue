<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxi5_9bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi5_9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:stairs-arrow-down-left" /></template>
