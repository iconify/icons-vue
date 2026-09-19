<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp_816eks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lp_816eks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:upload" /></template>
