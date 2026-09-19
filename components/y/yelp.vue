<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbosmackf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="tbosmackf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yelp" /></template>
