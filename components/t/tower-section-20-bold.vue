<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m53sf3b9t.css';
import '../../css/y/ylritbb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m53sf3b9t"/><path class="ylritbb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tower-section-20-bold" /></template>
