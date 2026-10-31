<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw2qafb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw2qafb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-fill-round" /></template>
