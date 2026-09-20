<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/e/eqnauu.css';
import '../../css/c/cmd1at.css';
import '../../css/u/u_cjuu.css';
import '../../css/c/cb6m_x.css';
import '../../css/s/so-from-48.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c eqnauu"/><circle class="cmd1at"/><path class="a0m25c u_cjuu"/><path class="a0m25c cb6m_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-remove" /></template>
