<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b581idbbf.css';
import '../../css/e/epme-tb1k.css';
import '../../css/i/iar3qwbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b581idbbf"/><path class="epme-tb1k"/><path class="iar3qwbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-broken" /></template>
