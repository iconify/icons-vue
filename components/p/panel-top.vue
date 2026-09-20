<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyv-pnb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyv-pnb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top" /></template>
