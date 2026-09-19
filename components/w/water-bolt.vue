<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_t2cbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xq_t2cbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-bolt" /></template>
