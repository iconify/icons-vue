<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi2_bml3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yi2_bml3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:skiing" /></template>
