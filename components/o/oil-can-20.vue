<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epgf2xatz.css';
import '../../css/y/ys1xrmbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="epgf2xatz"/><path class="ys1xrmbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-can-20" /></template>
