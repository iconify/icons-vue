<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd3rb99cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fd3rb99cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:steam-train-with-smiling-face-with-tires" /></template>
