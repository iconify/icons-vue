<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is3vjhbys.css';
import '../../css/w/wgy-1_e7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="is3vjhbys"/><path class="wgy-1_e7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:traefikmesh-wordmark" /></template>
