<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjzqy4bri.css';
import '../../css/s/swsnl4b_n.css';
import '../../css/y/yydc_tcsq.css';
import '../../css/t/tmo38wbpa.css';
import '../../css/e/e38acrb9a.css';
import '../../css/c/cktdxyblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fjzqy4bri"/><path class="swsnl4b_n"/><path class="yydc_tcsq"/><path class="tmo38wbpa"/><path class="e38acrb9a"/><path class="cktdxyblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:tuna" /></template>
