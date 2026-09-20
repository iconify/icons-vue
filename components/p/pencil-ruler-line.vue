<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n339tvehl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n339tvehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ruler-line" /></template>
