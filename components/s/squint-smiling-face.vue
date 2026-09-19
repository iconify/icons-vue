<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xug1g_b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xug1g_b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:squint-smiling-face" /></template>
