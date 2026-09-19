<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj481d2gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kj481d2gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:swiper" /></template>
