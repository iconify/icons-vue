<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo7956bee.css';
import '../../css/f/fq1o6q5xj.css';
import '../../css/j/jq1xa4bul.css';
import '../../css/e/e_r59bb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mo7956bee"/><path class="fq1o6q5xj"/><path class="jq1xa4bul"/><path class="e_r59bb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sando-light" /></template>
