<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voj5jfbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voj5jfbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:right-top-arrow-circle" /></template>
