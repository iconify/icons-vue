<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/doete9yan.css';
import '../../css/w/wsvb1rbkf.css';
import '../../css/p/p11hmpggb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="doete9yan"/><path class="wsvb1rbkf"/><path class="p11hmpggb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-broken" /></template>
