<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shw5dwbgv.css';
import '../../css/u/u9zmojb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shw5dwbgv"/><path class="u9zmojb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sharkord-dark" /></template>
