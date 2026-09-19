<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpc4d_bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpc4d_bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swan" /></template>
