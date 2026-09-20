<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrt0pxbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrt0pxbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stack-overflow-fill" /></template>
