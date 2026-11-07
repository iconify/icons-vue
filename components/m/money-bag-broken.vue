<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gwely914n.css';
import '../../css/e/eg-wi4b5c.css';
import '../../css/v/vltoy5rhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gwely914n"/><path class="eg-wi4b5c"/><path class="vltoy5rhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-broken" /></template>
