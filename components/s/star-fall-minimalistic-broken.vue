<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ln7kjcc0u.css';
import '../../css/c/cd47i0m6c.css';
import '../../css/q/qoddae6qt.css';
import '../../css/d/d7doq45qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ln7kjcc0u"/><path class="cd47i0m6c"/><path class="qoddae6qt"/><path class="d7doq45qw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-broken" /></template>
