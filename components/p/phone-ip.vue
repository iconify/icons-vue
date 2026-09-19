<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3n3nzbqe.css';
import '../../css/i/iv66tstfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w3n3nzbqe"/><path class="iv66tstfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-ip" /></template>
