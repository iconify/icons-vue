<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh0_e8b5g.css';
import '../../css/r/r0v7q4-zh.css';
import '../../css/a/a1c6c_bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh0_e8b5g"/><circle class="r0v7q4-zh"/><path class="a1c6c_bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oxker" /></template>
