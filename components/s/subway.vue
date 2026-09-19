<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do3r89v-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="do3r89v-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:subway" /></template>
