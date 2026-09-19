<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtiu8tb2k.css';
import '../../css/o/oxin_cb0v.css';
import '../../css/m/mt4ydix1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xtiu8tb2k"/><path class="oxin_cb0v"/><path class="mt4ydix1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mongoose-wordmark" /></template>
