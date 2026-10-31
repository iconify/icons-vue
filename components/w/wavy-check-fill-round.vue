<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsj340b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsj340b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-check-fill-round" /></template>
