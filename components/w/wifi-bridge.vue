<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/num_bkpuw.css';
import '../../css/b/bpv7jubps.css';
import '../../css/o/okk3kca1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="num_bkpuw"/><path class="bpv7jubps"/><path class="okk3kca1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi-bridge" /></template>
