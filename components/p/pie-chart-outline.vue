<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kav5bxc9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kav5bxc9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pie-chart-outline" /></template>
