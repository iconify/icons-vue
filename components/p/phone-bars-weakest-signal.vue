<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw52gbqmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cw52gbqmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bars-weakest-signal" /></template>
