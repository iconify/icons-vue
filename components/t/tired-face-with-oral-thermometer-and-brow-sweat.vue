<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xijr_zb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xijr_zb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-oral-thermometer-and-brow-sweat" /></template>
