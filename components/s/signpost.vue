<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcbnmxbuj.css';
import '../../css/r/rsf38h_ot.css';
import '../../css/g/gd4hxebuc.css';
import '../../css/i/isqiaxawv.css';
import '../../css/k/ksextccsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mcbnmxbuj"/><path class="rsf38h_ot"/><path class="gd4hxebuc"/><path class="isqiaxawv"/><path class="ksextccsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:signpost" /></template>
