<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wackrsbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wackrsbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:taco-bell" /></template>
