<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2t86ebiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d2t86ebiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map-marked" /></template>
