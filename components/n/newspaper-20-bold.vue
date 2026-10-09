<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39i0s06f.css';
import '../../css/m/muoqy1bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r39i0s06f"/><path class="muoqy1bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:newspaper-20-bold" /></template>
