<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adh2_0ble.css';
import '../../css/y/y0igkftrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="adh2_0ble"/><path class="y0igkftrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:right-arrow-curving-left" /></template>
