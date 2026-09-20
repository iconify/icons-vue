<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6jadbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn6jadbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-scroll-wheel" /></template>
