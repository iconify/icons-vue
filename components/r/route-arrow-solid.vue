<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2r5dbc3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2r5dbc3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:route-arrow-solid" /></template>
