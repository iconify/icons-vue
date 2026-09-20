<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ahplb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ahplb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-up-filled" /></template>
