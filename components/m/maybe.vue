<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc25svfcp.css';
import '../../css/j/jly7v7-2j.css';
import '../../css/f/f_km3v9ni.css';
import '../../css/a/afby5gqzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc25svfcp"/><path class="jly7v7-2j"/><path class="f_km3v9ni"/><path class="afby5gqzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maybe" /></template>
