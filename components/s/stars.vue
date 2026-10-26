<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w294ishiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w294ishiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:stars" /></template>
