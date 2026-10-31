<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/hru92mfxt.css';
import '../../css/o/oit8jiddo.css';
import '../../css/i/iqvhvkb5p.css';
import '../../css/f/f67p186iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="hru92mfxt wm-shadow"/><path class="oit8jiddo wm-shadow"/><path class="iqvhvkb5p"/><path class="f67p186iu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:receipt" /></template>
