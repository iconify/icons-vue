<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjji0eb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjji0eb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:navigation-fill" /></template>
