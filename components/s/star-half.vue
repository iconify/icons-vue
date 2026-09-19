<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_h2tywfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_h2tywfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:star-half" /></template>
