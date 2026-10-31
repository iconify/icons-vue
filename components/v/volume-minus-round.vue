<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttqtthb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttqtthb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-minus-round" /></template>
