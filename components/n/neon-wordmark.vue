<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/not8szbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="not8szbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:neon-wordmark" /></template>
