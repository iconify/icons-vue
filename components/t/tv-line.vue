<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otfnt6bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otfnt6bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tv-line" /></template>
