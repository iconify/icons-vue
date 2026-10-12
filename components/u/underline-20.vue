<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj8m3lbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mj8m3lbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:underline-20" /></template>
