<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1glutbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1glutbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:text-height" /></template>
