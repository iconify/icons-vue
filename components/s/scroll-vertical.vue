<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxsp-3jny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxsp-3jny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:scroll-vertical" /></template>
