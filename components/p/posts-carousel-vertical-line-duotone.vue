<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ye7qo4bza.css';
import '../../css/s/sp0979bhv.css';
import '../../css/s/sieuiccfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ye7qo4bza"/><path class="sp0979bhv"/><path class="sieuiccfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-line-duotone" /></template>
