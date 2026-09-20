<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvn40n5nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvn40n5nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:xiaomi-mimo" /></template>
