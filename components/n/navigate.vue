<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzjpee4cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzjpee4cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:navigate" /></template>
