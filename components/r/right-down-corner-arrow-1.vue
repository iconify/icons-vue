<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gta3qn_yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gta3qn_yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:right-down-corner-arrow-1" /></template>
