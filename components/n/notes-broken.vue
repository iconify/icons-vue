<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/da3rcub4c.css';
import '../../css/c/coyhggb-v.css';
import '../../css/n/ncaw82bqt.css';
import '../../css/h/h995enbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="da3rcub4c"/><path class="coyhggb-v"/><path class="ncaw82bqt"/><path class="h995enbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-broken" /></template>
