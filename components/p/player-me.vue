<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzbs20ffj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mzbs20ffj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:player-me" /></template>
