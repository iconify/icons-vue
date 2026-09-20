<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg4kqqb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hg4kqqb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:slider-end" /></template>
