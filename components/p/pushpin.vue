<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt0xhaboe.css';
import '../../css/i/ibygdfo4w.css';
import '../../css/x/xc__svjwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rt0xhaboe"/><path class="ibygdfo4w"/><path class="xc__svjwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pushpin" /></template>
