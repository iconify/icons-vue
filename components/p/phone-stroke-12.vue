<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgk69x2ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qgk69x2ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-stroke-12" /></template>
