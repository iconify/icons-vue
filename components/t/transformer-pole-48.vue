<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscmlob8u.css';
import '../../css/y/yynh_dbio.css';
import '../../css/n/nu071yljs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kscmlob8u"/><path class="yynh_dbio"/><path class="nu071yljs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transformer-pole-48" /></template>
