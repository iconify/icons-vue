<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6ve9rbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6ve9rbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remix-line" /></template>
