<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/at0-x07xm.css';
import '../../css/w/w1pxv4b2k.css';
import '../../css/e/evib1nbfc.css';
import '../../css/i/iurcs7brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="at0-x07xm"/><path class="w1pxv4b2k"/><path class="evib1nbfc"/><path class="iurcs7brt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-3-broken" /></template>
