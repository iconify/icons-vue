<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swka3acgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="swka3acgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taxi-checkerboard" /></template>
