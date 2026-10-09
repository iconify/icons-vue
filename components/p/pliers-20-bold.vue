<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drz3d56wa.css';
import '../../css/z/z2dsa8b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="drz3d56wa"/><path class="z2dsa8b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pliers-20-bold" /></template>
