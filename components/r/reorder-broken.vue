<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hfpr3cbbr.css';
import '../../css/o/oiy9mib8b.css';
import '../../css/h/hhlxfkbol.css';
import '../../css/h/hxd6ts2yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hfpr3cbbr"/><path class="oiy9mib8b"/><path class="hhlxfkbol"/><path class="hxd6ts2yz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-broken" /></template>
