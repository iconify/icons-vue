<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hqpl1bcby.css';
import '../../css/k/k9htqua9u.css';
import '../../css/p/p1tpmgbyh.css';
import '../../css/h/h6_ngrzeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hqpl1bcby"/><path class="k9htqua9u"/><path class="p1tpmgbyh"/><path class="h6_ngrzeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-3-line-duotone" /></template>
