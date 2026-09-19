<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zonioguau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zonioguau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-stroke-12" /></template>
