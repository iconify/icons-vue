<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/u4d5nhbqb.css';
import '../../css/a/afnfswcvd.css';
import '../../css/m/md3v46buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="u4d5nhbqb"/><path class="afnfswcvd"/><path class="md3v46buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:monkey-zodiac" /></template>
