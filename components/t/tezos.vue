<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da2ax3dpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":47,"height":64};
const content = `<path class="da2ax3dpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tezos" /></template>
