<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0i_05b_b.css';
import '../../css/m/mp3j7pbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v0i_05b_b"/><path class="mp3j7pbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meter-cabinet-20-bold" /></template>
