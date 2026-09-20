<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw9u178af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gw9u178af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:settings" /></template>
