<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp7js-igc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gp7js-igc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:quantopian" /></template>
