<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc6i9-j6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc6i9-j6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sweats-line" /></template>
