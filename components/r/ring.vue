<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf25pihft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf25pihft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ring" /></template>
