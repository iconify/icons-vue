<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fgrp_1b7a.css';
import '../../css/d/drgun2b_o.css';
import '../../css/w/wko_7ccxa.css';
import '../../css/n/ndj9-_i_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fgrp_1b7a"/><path class="drgun2b_o"/><path class="wko_7ccxa"/><path class="ndj9-_i_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-5-broken" /></template>
