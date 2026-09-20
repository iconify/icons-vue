<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8wp-wdvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8wp-wdvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-horizontal-filled" /></template>
