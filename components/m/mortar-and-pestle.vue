<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlr6yzbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nlr6yzbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mortar-and-pestle" /></template>
