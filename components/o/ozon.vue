<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtnow_b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":485,"height":106};
const content = `<path class="qtnow_b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ozon" /></template>
