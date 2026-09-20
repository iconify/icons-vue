<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew05xgb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew05xgb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmenux-dark" /></template>
