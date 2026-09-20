<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a8neukw-z.css';
import '../../css/a/ab350_zld.css';
import '../../css/x/x3z2s0btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="a8neukw-z"/><path class="ab350_zld"/><path class="x3z2s0btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-check-broken" /></template>
