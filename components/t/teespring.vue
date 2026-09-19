<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyr2k2qmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uyr2k2qmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:teespring" /></template>
