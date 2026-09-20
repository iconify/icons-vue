<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7gqk8bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m7gqk8bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:puzzle-piece-solid" /></template>
