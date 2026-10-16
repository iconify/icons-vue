<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu8m7-b_x.css';
import '../../css/y/ytutm3h1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uu8m7-b_x"/><path class="ytutm3h1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:siren-48" /></template>
