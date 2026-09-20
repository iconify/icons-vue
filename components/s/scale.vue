<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msxw39e1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="msxw39e1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:scale" /></template>
