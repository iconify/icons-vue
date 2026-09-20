<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg1uq6s2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg1uq6s2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seal-line" /></template>
