<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf5r4xb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kf5r4xb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-stroke-20" /></template>
