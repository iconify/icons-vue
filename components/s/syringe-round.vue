<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi41d3bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi41d3bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-round" /></template>
