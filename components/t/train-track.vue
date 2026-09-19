<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-ii4f7on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ii4f7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:train-track" /></template>
