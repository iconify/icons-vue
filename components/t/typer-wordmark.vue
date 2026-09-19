<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9_00hbai.css';
import '../../css/l/l_m-ojccy.css';
import '../../css/i/ib-739bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="z9_00hbai"/><rect class="l_m-ojccy"/><path class="ib-739bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typer-wordmark" /></template>
