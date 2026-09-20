<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvqwu8btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvqwu8btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:shape-hexagon" /></template>
