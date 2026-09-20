<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys8jn-fyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys8jn-fyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:telecoil" /></template>
