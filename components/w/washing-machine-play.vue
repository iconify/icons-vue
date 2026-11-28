<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2tlclbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2tlclbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:washing-machine-play" /></template>
