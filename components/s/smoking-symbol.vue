<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkf1x5yse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hkf1x5yse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:smoking-symbol" /></template>
