<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0g4jgwls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="r0g4jgwls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:pharmacy" /></template>
