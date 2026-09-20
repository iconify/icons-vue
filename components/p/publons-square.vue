<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfq21bb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rfq21bb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:publons-square" /></template>
