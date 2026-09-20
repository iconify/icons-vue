<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-g6p_te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mp-g6p_te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-four-one-one" /></template>
