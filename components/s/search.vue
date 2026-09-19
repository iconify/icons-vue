<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5505n_tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="m5505n_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:search" /></template>
