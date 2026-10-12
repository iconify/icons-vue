<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_36uib7w.css';
import '../../css/t/tli9a8yok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x_36uib7w"/><path class="tli9a8yok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stapler-20-bold" /></template>
