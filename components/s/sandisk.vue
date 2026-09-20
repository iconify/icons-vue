<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzpqusz2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1225};
const content = `<path class="qzpqusz2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sandisk" /></template>
