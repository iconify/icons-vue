<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-3o8k8yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-3o8k8yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:subway" /></template>
