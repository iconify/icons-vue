<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhskczy5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="lhskczy5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-pinterest" /></template>
