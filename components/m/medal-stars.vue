<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fih8feb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fih8feb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:medal-stars" /></template>
