<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lim_l8bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lim_l8bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifyleft" /></template>
