<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h83zg0bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h83zg0bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-step-backward" /></template>
