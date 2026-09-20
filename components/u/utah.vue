<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkw_m7m-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kkw_m7m-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utah" /></template>
