<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tba065b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tba065b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:stop" /></template>
