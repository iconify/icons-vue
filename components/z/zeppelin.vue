<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nx-ik2vqn.css';
import '../../css/v/v4v2fd20w.css';
import '../../css/z/zs6dehbct.css';
import '../../css/j/j2oc--1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx-ik2vqn"/><path class="v4v2fd20w"/><path class="zs6dehbct"/><path class="j2oc--1ks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zeppelin" /></template>
