<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-0y1ac1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-0y1ac1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sailboat-check" /></template>
