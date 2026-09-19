<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv8oerjzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1360,"height":1000};
const content = `<path class="vv8oerjzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:terminal" /></template>
