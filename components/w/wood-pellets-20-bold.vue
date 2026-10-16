<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lda668b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lda668b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-pellets-20-bold" /></template>
