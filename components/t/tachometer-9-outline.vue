<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nqfxi3m4a.css';
import '../../css/t/tz4emgb9r.css';
import '../../css/l/l4duz-dfx.css';
import '../../css/z/z2iqbq9uf.css';
import '../../css/c/cf0six4tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nqfxi3m4a"/><path clip-rule="evenodd" class="tz4emgb9r"/><path class="l4duz-dfx"/><path clip-rule="evenodd" class="z2iqbq9uf"/><path class="cf0six4tt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tachometer-9-outline" /></template>
