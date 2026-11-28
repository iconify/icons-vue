<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuq6snofp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuq6snofp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:music-heart" /></template>
