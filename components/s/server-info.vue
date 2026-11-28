<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlr2y0byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlr2y0byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:server-info" /></template>
