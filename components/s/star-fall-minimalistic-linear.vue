<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wk8gzub6u.css';
import '../../css/c/cd47i0m6c.css';
import '../../css/q/qoddae6qt.css';
import '../../css/d/d7doq45qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wk8gzub6u"/><path class="cd47i0m6c"/><path class="qoddae6qt"/><path class="d7doq45qw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-linear" /></template>
