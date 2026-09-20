<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krt54e2yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krt54e2yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:share-sharp" /></template>
