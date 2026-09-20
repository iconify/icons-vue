<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpwb5tbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpwb5tbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:square-root" /></template>
