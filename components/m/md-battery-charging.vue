<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8lcs_8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uo8lcs_8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-battery-charging" /></template>
