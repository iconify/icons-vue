<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaa3j5mot.css';
import '../../css/z/z8x18kbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="eaa3j5mot"/><path class="z8x18kbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:screen-split-v" /></template>
