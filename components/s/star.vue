<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vopw6rdda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vopw6rdda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:star" /></template>
