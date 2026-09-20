<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f_18xcbpp.css';
import '../../css/a/ab9oag7th.css';
import '../../css/z/z_d3a3bzf.css';
import '../../css/j/jlzv4qbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f_18xcbpp"/><path class="ab9oag7th"/><path class="z_d3a3bzf"/><path class="jlzv4qbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-broken" /></template>
