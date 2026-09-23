<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-uq5pno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-uq5pno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:whale" /></template>
