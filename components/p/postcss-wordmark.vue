<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt_jtfb1h.css';
import '../../css/g/gw8h__b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mt_jtfb1h"/><path class="gw8h__b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:postcss-wordmark" /></template>
