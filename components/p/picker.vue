<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq_h_l3hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sq_h_l3hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:picker" /></template>
