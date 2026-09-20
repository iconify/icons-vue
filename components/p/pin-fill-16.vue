<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8jx4vivo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f8jx4vivo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pin-fill-16" /></template>
