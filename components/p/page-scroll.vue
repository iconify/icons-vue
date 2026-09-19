<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_ojgx_e.css';
import '../../css/q/q-roxqdob.css';
import '../../css/o/oc7q7_bck.css';
import '../../css/k/kgeui_bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rp_ojgx_e"/><path class="q-roxqdob"/><path class="oc7q7_bck"/><path class="kgeui_bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:page-scroll" /></template>
