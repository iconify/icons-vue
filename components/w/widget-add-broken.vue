<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xwwl7-bgf.css';
import '../../css/s/smlcbcyjn.css';
import '../../css/n/nb29afbrg.css';
import '../../css/d/dt99itbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xwwl7-bgf"/><path class="smlcbcyjn"/><path class="nb29afbrg"/><path class="dt99itbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-add-broken" /></template>
